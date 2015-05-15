# React Notifications

## Installation

```
npm install --save react-notifications
```

## Usage

```js
var Notifications = require('../lib/Notifications');

var notifications = [
  {
    id: 1,
    title: 'Title',
    message: 'Message'
  },
  {
    id: 2,
    title: 'Title',
    message: 'Message'
  }
];

function handleRequestHide(notification){
  console.log(notification)
}

<Notifications notifications={notifications} onRequestHide={handleRequestHide}/>
```

## Props

- notifications: []
- onRequestHide: function(notification)

## Notification object

```js
{
  id: [number],
  title: [string],
  message: 'String',
  timeOut: [milliseconds],
  onClick: [function]
}
```

## Example
View [demo](http://vn38minhtran.github.io/react-notifications) or example folder.