## SYNOPSIS
Simple JavaScript event controller implementation. Similar to Node.js `EventEmitter`, but controls a single event only.

## USAGE

```js
var EventController = require('event-controller');

var event1 = new EventController();

// Add listener
event1.add(function (value) {
  // handle event
});

event1.dispatch('hello');
```

##LICENSE

Apache License, Version 2.0
