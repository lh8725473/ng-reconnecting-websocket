ng-ReconnectingWebSocket
=====================
Usage

.controller('SomeController', function (ngSocket) {
  //Open a WebSocket connection
  var ws = ngSocket('ws://foo/bar');

  //Can call before socket has opened
  ws.send({foo: 'bar'});
});

### Forked Features



