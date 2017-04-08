# api documentation for  [socket.io-client (v1.7.3)](https://github.com/Automattic/socket.io-client#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-socket.io-client.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-socket.io-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-socket.io-client.svg)](https://travis-ci.org/npmdoc/node-npmdoc-socket.io-client)
#### [![Build Status](https://secure.travis-ci.org/socketio/socket.io-client.svg?branch=master)](http://travis-ci.org/socketio/socket.io-client) [![Dependency Status](https://david-dm.org/socketio/socket.io-client.svg)](https://david-dm.org/socketio/socket.io-

[![NPM](https://nodei.co/npm/socket.io-client.png?downloads=true)](https://www.npmjs.com/package/socket.io-client)

[![apidoc](https://npmdoc.github.io/node-npmdoc-socket.io-client/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-socket.io-client%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-socket.io-client/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-socket.io-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-socket.io-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/Automattic/socket.io-client/issues"
    },
    "contributors": [
        {
            "name": "Guillermo Rauch",
            "email": "rauchg@gmail.com"
        },
        {
            "name": "Arnout Kazemier",
            "email": "info@3rd-eden.com"
        },
        {
            "name": "Vladimir Dronnikov",
            "email": "dronnikov@gmail.com"
        },
        {
            "name": "Einar Otto Stangvik",
            "email": "einaros@gmail.com"
        }
    ],
    "dependencies": {
        "backo2": "1.0.2",
        "component-bind": "1.0.0",
        "component-emitter": "1.2.1",
        "debug": "2.3.3",
        "engine.io-client": "1.8.3",
        "has-binary": "0.1.7",
        "indexof": "0.0.1",
        "object-component": "0.0.3",
        "parseuri": "0.0.5",
        "socket.io-parser": "2.3.1",
        "to-array": "0.1.4"
    },
    "description": "[![Build Status](https://secure.travis-ci.org/socketio/socket.io-client.svg?branch=master)](http://travis-ci.org/socketio/socket.io-client) [![Dependency Status](https://david-dm.org/socketio/socket.io-client.svg)](https://david-dm.org/socketio/socket.io-",
    "devDependencies": {
        "babel-core": "6.4.5",
        "babel-eslint": "4.1.7",
        "babel-loader": "6.2.1",
        "babel-preset-es2015": "6.3.13",
        "base64-arraybuffer": "0.1.5",
        "concat-stream": "1.5.1",
        "derequire": "2.0.3",
        "eslint-config-standard": "4.4.0",
        "eslint-plugin-standard": "1.3.1",
        "expect.js": "0.3.1",
        "gulp": "3.9.0",
        "gulp-eslint": "1.1.1",
        "gulp-file": "0.2.0",
        "gulp-istanbul": "0.10.3",
        "gulp-minify": "0.0.14",
        "gulp-mocha": "2.2.0",
        "gulp-task-listing": "1.0.1",
        "has-cors": "1.1.0",
        "imports-loader": "^0.6.5",
        "istanbul": "0.4.2",
        "mocha": "2.3.4",
        "socket.io": "1.7.3",
        "strip-loader": "0.1.2",
        "text-blob-builder": "0.0.1",
        "uglify-js": "2.6.1",
        "webpack-stream": "3.2.0",
        "zuul": "3.11.0",
        "zuul-builder-webpack": "1.1.0",
        "zuul-ngrok": "4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b30e86aa10d5ef3546601c09cde4765e381da377",
        "tarball": "https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.7.3.tgz"
    },
    "files": [
        "lib/",
        "dist/"
    ],
    "gitHead": "dc76b53805eeecc84fd5c07952baa842369e59fe",
    "homepage": "https://github.com/Automattic/socket.io-client#readme",
    "keywords": [
        "realtime",
        "framework",
        "websocket",
        "tcp",
        "events",
        "client"
    ],
    "license": "MIT",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "darrachequesne",
            "email": "damien.arrachequesne@gmail.com"
        },
        {
            "name": "rauchg",
            "email": "rauchg@gmail.com"
        }
    ],
    "name": "socket.io-client",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Automattic/socket.io-client.git"
    },
    "scripts": {
        "test": "gulp test"
    },
    "version": "1.7.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module socket.io-client](#apidoc.module.socket.io-client)
1.  [function <span class="apidocSignatureSpan">socket.io-client.</span>Manager (uri, opts)](#apidoc.element.socket.io-client.Manager)
1.  [function <span class="apidocSignatureSpan">socket.io-client.</span>Socket (io, nsp, opts)](#apidoc.element.socket.io-client.Socket)
1.  [function <span class="apidocSignatureSpan">socket.io-client.</span>connect (uri, opts)](#apidoc.element.socket.io-client.connect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.</span>io-client.Manager (uri, opts)](#apidoc.element.socket.io-client.io-client.Manager)
1.  [function <span class="apidocSignatureSpan">socket.io-client.</span>io-client.Socket (io, nsp, opts)](#apidoc.element.socket.io-client.io-client.Socket)
1.  number <span class="apidocSignatureSpan">socket.io-client.</span>protocol
1.  object <span class="apidocSignatureSpan">socket.io-client.</span>io-client.Manager.prototype
1.  object <span class="apidocSignatureSpan">socket.io-client.</span>io-client.Socket.prototype
1.  object <span class="apidocSignatureSpan">socket.io-client.</span>managers

#### [module socket.io-client.Manager](#apidoc.module.socket.io-client.Manager)
1.  [function <span class="apidocSignatureSpan">socket.io-client.</span>Manager (uri, opts)](#apidoc.element.socket.io-client.Manager.Manager)

#### [module socket.io-client.Manager.prototype](#apidoc.module.socket.io-client.Manager.prototype)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>addEventListener (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.addEventListener)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>cleanup ()](#apidoc.element.socket.io-client.Manager.prototype.cleanup)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>close ()](#apidoc.element.socket.io-client.Manager.prototype.close)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>connect (fn, opts)](#apidoc.element.socket.io-client.Manager.prototype.connect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>destroy (socket)](#apidoc.element.socket.io-client.Manager.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>disconnect ()](#apidoc.element.socket.io-client.Manager.prototype.disconnect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>emit (event)](#apidoc.element.socket.io-client.Manager.prototype.emit)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>emitAll ()](#apidoc.element.socket.io-client.Manager.prototype.emitAll)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>hasListeners (event)](#apidoc.element.socket.io-client.Manager.prototype.hasListeners)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>listeners (event)](#apidoc.element.socket.io-client.Manager.prototype.listeners)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>maybeReconnectOnOpen ()](#apidoc.element.socket.io-client.Manager.prototype.maybeReconnectOnOpen)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>off (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.off)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>on (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.on)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>once (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.once)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onclose (reason)](#apidoc.element.socket.io-client.Manager.prototype.onclose)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>ondata (data)](#apidoc.element.socket.io-client.Manager.prototype.ondata)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>ondecoded (packet)](#apidoc.element.socket.io-client.Manager.prototype.ondecoded)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onerror (err)](#apidoc.element.socket.io-client.Manager.prototype.onerror)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onopen ()](#apidoc.element.socket.io-client.Manager.prototype.onopen)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onping ()](#apidoc.element.socket.io-client.Manager.prototype.onping)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onpong ()](#apidoc.element.socket.io-client.Manager.prototype.onpong)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onreconnect ()](#apidoc.element.socket.io-client.Manager.prototype.onreconnect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>open (fn, opts)](#apidoc.element.socket.io-client.Manager.prototype.open)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>packet (packet)](#apidoc.element.socket.io-client.Manager.prototype.packet)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>processPacketQueue ()](#apidoc.element.socket.io-client.Manager.prototype.processPacketQueue)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>randomizationFactor (v)](#apidoc.element.socket.io-client.Manager.prototype.randomizationFactor)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnect ()](#apidoc.element.socket.io-client.Manager.prototype.reconnect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnection (v)](#apidoc.element.socket.io-client.Manager.prototype.reconnection)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnectionAttempts (v)](#apidoc.element.socket.io-client.Manager.prototype.reconnectionAttempts)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnectionDelay (v)](#apidoc.element.socket.io-client.Manager.prototype.reconnectionDelay)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnectionDelayMax (v)](#apidoc.element.socket.io-client.Manager.prototype.reconnectionDelayMax)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>removeAllListeners (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>removeEventListener (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.removeEventListener)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>removeListener (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.removeListener)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>socket (nsp, opts)](#apidoc.element.socket.io-client.Manager.prototype.socket)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>timeout (v)](#apidoc.element.socket.io-client.Manager.prototype.timeout)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>updateSocketIds ()](#apidoc.element.socket.io-client.Manager.prototype.updateSocketIds)

#### [module socket.io-client.Socket](#apidoc.module.socket.io-client.Socket)
1.  [function <span class="apidocSignatureSpan">socket.io-client.</span>Socket (io, nsp, opts)](#apidoc.element.socket.io-client.Socket.Socket)

#### [module socket.io-client.Socket.prototype](#apidoc.module.socket.io-client.Socket.prototype)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>ack (id)](#apidoc.element.socket.io-client.Socket.prototype.ack)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>addEventListener (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.addEventListener)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>close ()](#apidoc.element.socket.io-client.Socket.prototype.close)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>compress (compress)](#apidoc.element.socket.io-client.Socket.prototype.compress)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>connect ()](#apidoc.element.socket.io-client.Socket.prototype.connect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>destroy ()](#apidoc.element.socket.io-client.Socket.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>disconnect ()](#apidoc.element.socket.io-client.Socket.prototype.disconnect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>emit (ev)](#apidoc.element.socket.io-client.Socket.prototype.emit)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>emitBuffered ()](#apidoc.element.socket.io-client.Socket.prototype.emitBuffered)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>hasListeners (event)](#apidoc.element.socket.io-client.Socket.prototype.hasListeners)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>listeners (event)](#apidoc.element.socket.io-client.Socket.prototype.listeners)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>off (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.off)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>on (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.on)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onack (packet)](#apidoc.element.socket.io-client.Socket.prototype.onack)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>once (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.once)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onclose (reason)](#apidoc.element.socket.io-client.Socket.prototype.onclose)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onconnect ()](#apidoc.element.socket.io-client.Socket.prototype.onconnect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>ondisconnect ()](#apidoc.element.socket.io-client.Socket.prototype.ondisconnect)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onevent (packet)](#apidoc.element.socket.io-client.Socket.prototype.onevent)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onopen ()](#apidoc.element.socket.io-client.Socket.prototype.onopen)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onpacket (packet)](#apidoc.element.socket.io-client.Socket.prototype.onpacket)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>open ()](#apidoc.element.socket.io-client.Socket.prototype.open)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>packet (packet)](#apidoc.element.socket.io-client.Socket.prototype.packet)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>removeAllListeners (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>removeEventListener (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.removeEventListener)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>removeListener (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.removeListener)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>send ()](#apidoc.element.socket.io-client.Socket.prototype.send)
1.  [function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>subEvents ()](#apidoc.element.socket.io-client.Socket.prototype.subEvents)



# <a name="apidoc.module.socket.io-client"></a>[module socket.io-client](#apidoc.module.socket.io-client)

#### <a name="apidoc.element.socket.io-client.Manager"></a>[function <span class="apidocSignatureSpan">socket.io-client.</span>Manager (uri, opts)](#apidoc.element.socket.io-client.Manager)
- description and source-code
```javascript
function Manager(uri, opts) {
  if (!(this instanceof Manager)) return new Manager(uri, opts);
  if (uri && ('object' === typeof uri)) {
    opts = uri;
    uri = undefined;
  }
  opts = opts || {};

  opts.path = opts.path || '/socket.io';
  this.nsps = {};
  this.subs = [];
  this.opts = opts;
  this.reconnection(opts.reconnection !== false);
  this.reconnectionAttempts(opts.reconnectionAttempts || Infinity);
  this.reconnectionDelay(opts.reconnectionDelay || 1000);
  this.reconnectionDelayMax(opts.reconnectionDelayMax || 5000);
  this.randomizationFactor(opts.randomizationFactor || 0.5);
  this.backoff = new Backoff({
    min: this.reconnectionDelay(),
    max: this.reconnectionDelayMax(),
    jitter: this.randomizationFactor()
  });
  this.timeout(null == opts.timeout ? 20000 : opts.timeout);
  this.readyState = 'closed';
  this.uri = uri;
  this.connecting = [];
  this.lastPing = null;
  this.encoding = false;
  this.packetBuffer = [];
  this.encoder = new parser.Encoder();
  this.decoder = new parser.Decoder();
  this.autoConnect = opts.autoConnect !== false;
  if (this.autoConnect) this.open();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket"></a>[function <span class="apidocSignatureSpan">socket.io-client.</span>Socket (io, nsp, opts)](#apidoc.element.socket.io-client.Socket)
- description and source-code
```javascript
function Socket(io, nsp, opts) {
  this.io = io;
  this.nsp = nsp;
  this.json = this; // compat
  this.ids = 0;
  this.acks = {};
  this.receiveBuffer = [];
  this.sendBuffer = [];
  this.connected = false;
  this.disconnected = true;
  if (opts && opts.query) {
    this.query = opts.query;
  }
  if (this.io.autoConnect) this.open();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.connect"></a>[function <span class="apidocSignatureSpan">socket.io-client.</span>connect (uri, opts)](#apidoc.element.socket.io-client.connect)
- description and source-code
```javascript
function lookup(uri, opts) {
  if (typeof uri === 'object') {
    opts = uri;
    uri = undefined;
  }

  opts = opts || {};

  var parsed = url(uri);
  var source = parsed.source;
  var id = parsed.id;
  var path = parsed.path;
  var sameNamespace = cache[id] && path in cache[id].nsps;
  var newConnection = opts.forceNew || opts['force new connection'] ||
                      false === opts.multiplex || sameNamespace;

  var io;

  if (newConnection) {
    debug('ignoring socket cache for %s', source);
    io = Manager(source, opts);
  } else {
    if (!cache[id]) {
      debug('new io instance for %s', source);
      cache[id] = Manager(source, opts);
    }
    io = cache[id];
  }
  if (parsed.query && !opts.query) {
    opts.query = parsed.query;
  } else if (opts && 'object' === typeof opts.query) {
    opts.query = encodeQueryString(opts.query);
  }
  return io.socket(parsed.path, opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.io-client.Manager"></a>[function <span class="apidocSignatureSpan">socket.io-client.</span>io-client.Manager (uri, opts)](#apidoc.element.socket.io-client.io-client.Manager)
- description and source-code
```javascript
function Manager(uri, opts) {
  if (!(this instanceof Manager)) return new Manager(uri, opts);
  if (uri && ('object' === typeof uri)) {
    opts = uri;
    uri = undefined;
  }
  opts = opts || {};

  opts.path = opts.path || '/socket.io';
  this.nsps = {};
  this.subs = [];
  this.opts = opts;
  this.reconnection(opts.reconnection !== false);
  this.reconnectionAttempts(opts.reconnectionAttempts || Infinity);
  this.reconnectionDelay(opts.reconnectionDelay || 1000);
  this.reconnectionDelayMax(opts.reconnectionDelayMax || 5000);
  this.randomizationFactor(opts.randomizationFactor || 0.5);
  this.backoff = new Backoff({
    min: this.reconnectionDelay(),
    max: this.reconnectionDelayMax(),
    jitter: this.randomizationFactor()
  });
  this.timeout(null == opts.timeout ? 20000 : opts.timeout);
  this.readyState = 'closed';
  this.uri = uri;
  this.connecting = [];
  this.lastPing = null;
  this.encoding = false;
  this.packetBuffer = [];
  this.encoder = new parser.Encoder();
  this.decoder = new parser.Decoder();
  this.autoConnect = opts.autoConnect !== false;
  if (this.autoConnect) this.open();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.io-client.Socket"></a>[function <span class="apidocSignatureSpan">socket.io-client.</span>io-client.Socket (io, nsp, opts)](#apidoc.element.socket.io-client.io-client.Socket)
- description and source-code
```javascript
function Socket(io, nsp, opts) {
  this.io = io;
  this.nsp = nsp;
  this.json = this; // compat
  this.ids = 0;
  this.acks = {};
  this.receiveBuffer = [];
  this.sendBuffer = [];
  this.connected = false;
  this.disconnected = true;
  if (opts && opts.query) {
    this.query = opts.query;
  }
  if (this.io.autoConnect) this.open();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socket.io-client.Manager"></a>[module socket.io-client.Manager](#apidoc.module.socket.io-client.Manager)

#### <a name="apidoc.element.socket.io-client.Manager.Manager"></a>[function <span class="apidocSignatureSpan">socket.io-client.</span>Manager (uri, opts)](#apidoc.element.socket.io-client.Manager.Manager)
- description and source-code
```javascript
function Manager(uri, opts) {
  if (!(this instanceof Manager)) return new Manager(uri, opts);
  if (uri && ('object' === typeof uri)) {
    opts = uri;
    uri = undefined;
  }
  opts = opts || {};

  opts.path = opts.path || '/socket.io';
  this.nsps = {};
  this.subs = [];
  this.opts = opts;
  this.reconnection(opts.reconnection !== false);
  this.reconnectionAttempts(opts.reconnectionAttempts || Infinity);
  this.reconnectionDelay(opts.reconnectionDelay || 1000);
  this.reconnectionDelayMax(opts.reconnectionDelayMax || 5000);
  this.randomizationFactor(opts.randomizationFactor || 0.5);
  this.backoff = new Backoff({
    min: this.reconnectionDelay(),
    max: this.reconnectionDelayMax(),
    jitter: this.randomizationFactor()
  });
  this.timeout(null == opts.timeout ? 20000 : opts.timeout);
  this.readyState = 'closed';
  this.uri = uri;
  this.connecting = [];
  this.lastPing = null;
  this.encoding = false;
  this.packetBuffer = [];
  this.encoder = new parser.Encoder();
  this.decoder = new parser.Decoder();
  this.autoConnect = opts.autoConnect !== false;
  if (this.autoConnect) this.open();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socket.io-client.Manager.prototype"></a>[module socket.io-client.Manager.prototype](#apidoc.module.socket.io-client.Manager.prototype)

#### <a name="apidoc.element.socket.io-client.Manager.prototype.addEventListener"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>addEventListener (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.addEventListener)
- description and source-code
```javascript
addEventListener = function (event, fn){
  this._callbacks = this._callbacks || {};
  (this._callbacks['$' + event] = this._callbacks['$' + event] || [])
    .push(fn);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.cleanup"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>cleanup ()](#apidoc.element.socket.io-client.Manager.prototype.cleanup)
- description and source-code
```javascript
cleanup = function () {
  debug('cleanup');

  var subsLength = this.subs.length;
  for (var i = 0; i < subsLength; i++) {
    var sub = this.subs.shift();
    sub.destroy();
  }

  this.packetBuffer = [];
  this.encoding = false;
  this.lastPing = null;

  this.decoder.destroy();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.close"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>close ()](#apidoc.element.socket.io-client.Manager.prototype.close)
- description and source-code
```javascript
close = function () {
  debug('disconnect');
  this.skipReconnect = true;
  this.reconnecting = false;
  if ('opening' === this.readyState) {
    // 'onclose' will not fire because
    // an open event never happened
    this.cleanup();
  }
  this.backoff.reset();
  this.readyState = 'closed';
  if (this.engine) this.engine.close();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.connect"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>connect (fn, opts)](#apidoc.element.socket.io-client.Manager.prototype.connect)
- description and source-code
```javascript
connect = function (fn, opts) {
  debug('readyState %s', this.readyState);
  if (~this.readyState.indexOf('open')) return this;

  debug('opening %s', this.uri);
  this.engine = eio(this.uri, this.opts);
  var socket = this.engine;
  var self = this;
  this.readyState = 'opening';
  this.skipReconnect = false;

  // emit 'open'
  var openSub = on(socket, 'open', function () {
    self.onopen();
    fn && fn();
  });

  // emit 'connect_error'
  var errorSub = on(socket, 'error', function (data) {
    debug('connect_error');
    self.cleanup();
    self.readyState = 'closed';
    self.emitAll('connect_error', data);
    if (fn) {
      var err = new Error('Connection error');
      err.data = data;
      fn(err);
    } else {
      // Only do this if there is no fn to handle the error
      self.maybeReconnectOnOpen();
    }
  });

  // emit 'connect_timeout'
  if (false !== this._timeout) {
    var timeout = this._timeout;
    debug('connect attempt will timeout after %d', timeout);

    // set timer
    var timer = setTimeout(function () {
      debug('connect attempt timed out after %d', timeout);
      openSub.destroy();
      socket.close();
      socket.emit('error', 'timeout');
      self.emitAll('connect_timeout', timeout);
    }, timeout);

    this.subs.push({
      destroy: function () {
        clearTimeout(timer);
      }
    });
  }

  this.subs.push(openSub);
  this.subs.push(errorSub);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.destroy"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>destroy (socket)](#apidoc.element.socket.io-client.Manager.prototype.destroy)
- description and source-code
```javascript
destroy = function (socket) {
  var index = indexOf(this.connecting, socket);
  if (~index) this.connecting.splice(index, 1);
  if (this.connecting.length) return;

  this.close();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.disconnect"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>disconnect ()](#apidoc.element.socket.io-client.Manager.prototype.disconnect)
- description and source-code
```javascript
disconnect = function () {
  debug('disconnect');
  this.skipReconnect = true;
  this.reconnecting = false;
  if ('opening' === this.readyState) {
    // 'onclose' will not fire because
    // an open event never happened
    this.cleanup();
  }
  this.backoff.reset();
  this.readyState = 'closed';
  if (this.engine) this.engine.close();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.emit"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>emit (event)](#apidoc.element.socket.io-client.Manager.prototype.emit)
- description and source-code
```javascript
emit = function (event){
  this._callbacks = this._callbacks || {};
  var args = [].slice.call(arguments, 1)
    , callbacks = this._callbacks['$' + event];

  if (callbacks) {
    callbacks = callbacks.slice(0);
    for (var i = 0, len = callbacks.length; i < len; ++i) {
      callbacks[i].apply(this, args);
    }
  }

  return this;
}
```
- example usage
```shell
...

#### Socket#compress(v:Boolean):Socket

Sets a modifier for a subsequent event emission that the event data will
only be _compressed_ if the value is 'true'. Defaults to 'true' when you don't call the method.

'''js
socket.compress(false).emit('an event', { some: 'data' });
'''

#### Events

- 'connect'. Fired upon a connection including a successful reconnection.
- 'error'. Fired upon a connection error
  Parameters:
...
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.emitAll"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>emitAll ()](#apidoc.element.socket.io-client.Manager.prototype.emitAll)
- description and source-code
```javascript
emitAll = function () {
  this.emit.apply(this, arguments);
  for (var nsp in this.nsps) {
    if (has.call(this.nsps, nsp)) {
      this.nsps[nsp].emit.apply(this.nsps[nsp], arguments);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.hasListeners"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>hasListeners (event)](#apidoc.element.socket.io-client.Manager.prototype.hasListeners)
- description and source-code
```javascript
hasListeners = function (event){
  return !! this.listeners(event).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.listeners"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>listeners (event)](#apidoc.element.socket.io-client.Manager.prototype.listeners)
- description and source-code
```javascript
listeners = function (event){
  this._callbacks = this._callbacks || {};
  return this._callbacks['$' + event] || [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.maybeReconnectOnOpen"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>maybeReconnectOnOpen ()](#apidoc.element.socket.io-client.Manager.prototype.maybeReconnectOnOpen)
- description and source-code
```javascript
maybeReconnectOnOpen = function () {
  // Only try to reconnect if it's the first time we're connecting
  if (!this.reconnecting && this._reconnection && this.backoff.attempts === 0) {
    // keeps reconnection from firing twice for the same reconnection loop
    this.reconnect();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.off"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>off (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.off)
- description and source-code
```javascript
off = function (event, fn){
  this._callbacks = this._callbacks || {};

  // all
  if (0 == arguments.length) {
    this._callbacks = {};
    return this;
  }

  // specific event
  var callbacks = this._callbacks['$' + event];
  if (!callbacks) return this;

  // remove all handlers
  if (1 == arguments.length) {
    delete this._callbacks['$' + event];
    return this;
  }

  // remove specific handler
  var cb;
  for (var i = 0; i < callbacks.length; i++) {
    cb = callbacks[i];
    if (cb === fn || cb.fn === fn) {
      callbacks.splice(i, 1);
      break;
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.on"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>on (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.on)
- description and source-code
```javascript
on = function (event, fn){
  this._callbacks = this._callbacks || {};
  (this._callbacks['$' + event] = this._callbacks['$' + event] || [])
    .push(fn);
  return this;
}
```
- example usage
```shell
...
socket.io server as '/socket.io/socket.io.js'. Alternatively you can
serve the file 'socket.io.js' or 'socket.io.min.js' found in the 'dist' folder.

'''html
<script src="/socket.io/socket.io.js"></script>
<script>
  var socket = io('http://localhost');
  socket.on('connect', function(){});
  socket.on('event', function(data){});
  socket.on('disconnect', function(){});
</script>
'''

Socket.IO is compatible with [browserify](http://browserify.org/).
...
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.once"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>once (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.once)
- description and source-code
```javascript
once = function (event, fn){
  function on() {
    this.off(event, on);
    fn.apply(this, arguments);
  }

  on.fn = fn;
  this.on(event, on);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.onclose"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onclose (reason)](#apidoc.element.socket.io-client.Manager.prototype.onclose)
- description and source-code
```javascript
onclose = function (reason) {
  debug('onclose');

  this.cleanup();
  this.backoff.reset();
  this.readyState = 'closed';
  this.emit('close', reason);

  if (this._reconnection && !this.skipReconnect) {
    this.reconnect();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.ondata"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>ondata (data)](#apidoc.element.socket.io-client.Manager.prototype.ondata)
- description and source-code
```javascript
ondata = function (data) {
  this.decoder.add(data);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.ondecoded"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>ondecoded (packet)](#apidoc.element.socket.io-client.Manager.prototype.ondecoded)
- description and source-code
```javascript
ondecoded = function (packet) {
  this.emit('packet', packet);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.onerror"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onerror (err)](#apidoc.element.socket.io-client.Manager.prototype.onerror)
- description and source-code
```javascript
onerror = function (err) {
  debug('error', err);
  this.emitAll('error', err);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.onopen"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onopen ()](#apidoc.element.socket.io-client.Manager.prototype.onopen)
- description and source-code
```javascript
onopen = function () {
  debug('open');

  // clear old subs
  this.cleanup();

  // mark as open
  this.readyState = 'open';
  this.emit('open');

  // add new subs
  var socket = this.engine;
  this.subs.push(on(socket, 'data', bind(this, 'ondata')));
  this.subs.push(on(socket, 'ping', bind(this, 'onping')));
  this.subs.push(on(socket, 'pong', bind(this, 'onpong')));
  this.subs.push(on(socket, 'error', bind(this, 'onerror')));
  this.subs.push(on(socket, 'close', bind(this, 'onclose')));
  this.subs.push(on(this.decoder, 'decoded', bind(this, 'ondecoded')));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.onping"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onping ()](#apidoc.element.socket.io-client.Manager.prototype.onping)
- description and source-code
```javascript
onping = function () {
  this.lastPing = new Date();
  this.emitAll('ping');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.onpong"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onpong ()](#apidoc.element.socket.io-client.Manager.prototype.onpong)
- description and source-code
```javascript
onpong = function () {
  this.emitAll('pong', new Date() - this.lastPing);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.onreconnect"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>onreconnect ()](#apidoc.element.socket.io-client.Manager.prototype.onreconnect)
- description and source-code
```javascript
onreconnect = function () {
  var attempt = this.backoff.attempts;
  this.reconnecting = false;
  this.backoff.reset();
  this.updateSocketIds();
  this.emitAll('reconnect', attempt);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.open"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>open (fn, opts)](#apidoc.element.socket.io-client.Manager.prototype.open)
- description and source-code
```javascript
open = function (fn, opts) {
  debug('readyState %s', this.readyState);
  if (~this.readyState.indexOf('open')) return this;

  debug('opening %s', this.uri);
  this.engine = eio(this.uri, this.opts);
  var socket = this.engine;
  var self = this;
  this.readyState = 'opening';
  this.skipReconnect = false;

  // emit 'open'
  var openSub = on(socket, 'open', function () {
    self.onopen();
    fn && fn();
  });

  // emit 'connect_error'
  var errorSub = on(socket, 'error', function (data) {
    debug('connect_error');
    self.cleanup();
    self.readyState = 'closed';
    self.emitAll('connect_error', data);
    if (fn) {
      var err = new Error('Connection error');
      err.data = data;
      fn(err);
    } else {
      // Only do this if there is no fn to handle the error
      self.maybeReconnectOnOpen();
    }
  });

  // emit 'connect_timeout'
  if (false !== this._timeout) {
    var timeout = this._timeout;
    debug('connect attempt will timeout after %d', timeout);

    // set timer
    var timer = setTimeout(function () {
      debug('connect attempt timed out after %d', timeout);
      openSub.destroy();
      socket.close();
      socket.emit('error', 'timeout');
      self.emitAll('connect_timeout', timeout);
    }, timeout);

    this.subs.push({
      destroy: function () {
        clearTimeout(timer);
      }
    });
  }

  this.subs.push(openSub);
  this.subs.push(errorSub);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.packet"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>packet (packet)](#apidoc.element.socket.io-client.Manager.prototype.packet)
- description and source-code
```javascript
packet = function (packet) {
  debug('writing packet %j', packet);
  var self = this;
  if (packet.query && packet.type === 0) packet.nsp += '?' + packet.query;

  if (!self.encoding) {
    // encode, then write to engine with result
    self.encoding = true;
    this.encoder.encode(packet, function (encodedPackets) {
      for (var i = 0; i < encodedPackets.length; i++) {
        self.engine.write(encodedPackets[i], packet.options);
      }
      self.encoding = false;
      self.processPacketQueue();
    });
  } else { // add packet to the queue
    self.packetBuffer.push(packet);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.processPacketQueue"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>processPacketQueue ()](#apidoc.element.socket.io-client.Manager.prototype.processPacketQueue)
- description and source-code
```javascript
processPacketQueue = function () {
  if (this.packetBuffer.length > 0 && !this.encoding) {
    var pack = this.packetBuffer.shift();
    this.packet(pack);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.randomizationFactor"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>randomizationFactor (v)](#apidoc.element.socket.io-client.Manager.prototype.randomizationFactor)
- description and source-code
```javascript
randomizationFactor = function (v) {
  if (!arguments.length) return this._randomizationFactor;
  this._randomizationFactor = v;
  this.backoff && this.backoff.setJitter(v);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.reconnect"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnect ()](#apidoc.element.socket.io-client.Manager.prototype.reconnect)
- description and source-code
```javascript
reconnect = function () {
  if (this.reconnecting || this.skipReconnect) return this;

  var self = this;

  if (this.backoff.attempts >= this._reconnectionAttempts) {
    debug('reconnect failed');
    this.backoff.reset();
    this.emitAll('reconnect_failed');
    this.reconnecting = false;
  } else {
    var delay = this.backoff.duration();
    debug('will wait %dms before reconnect attempt', delay);

    this.reconnecting = true;
    var timer = setTimeout(function () {
      if (self.skipReconnect) return;

      debug('attempting reconnect');
      self.emitAll('reconnect_attempt', self.backoff.attempts);
      self.emitAll('reconnecting', self.backoff.attempts);

      // check again for the case socket closed in above events
      if (self.skipReconnect) return;

      self.open(function (err) {
        if (err) {
          debug('reconnect attempt error');
          self.reconnecting = false;
          self.reconnect();
          self.emitAll('reconnect_error', err.data);
        } else {
          debug('reconnect success');
          self.onreconnect();
        }
      });
    }, delay);

    this.subs.push({
      destroy: function () {
        clearTimeout(timer);
      }
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.reconnection"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnection (v)](#apidoc.element.socket.io-client.Manager.prototype.reconnection)
- description and source-code
```javascript
reconnection = function (v) {
  if (!arguments.length) return this._reconnection;
  this._reconnection = !!v;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.reconnectionAttempts"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnectionAttempts (v)](#apidoc.element.socket.io-client.Manager.prototype.reconnectionAttempts)
- description and source-code
```javascript
reconnectionAttempts = function (v) {
  if (!arguments.length) return this._reconnectionAttempts;
  this._reconnectionAttempts = v;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.reconnectionDelay"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnectionDelay (v)](#apidoc.element.socket.io-client.Manager.prototype.reconnectionDelay)
- description and source-code
```javascript
reconnectionDelay = function (v) {
  if (!arguments.length) return this._reconnectionDelay;
  this._reconnectionDelay = v;
  this.backoff && this.backoff.setMin(v);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.reconnectionDelayMax"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>reconnectionDelayMax (v)](#apidoc.element.socket.io-client.Manager.prototype.reconnectionDelayMax)
- description and source-code
```javascript
reconnectionDelayMax = function (v) {
  if (!arguments.length) return this._reconnectionDelayMax;
  this._reconnectionDelayMax = v;
  this.backoff && this.backoff.setMax(v);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>removeAllListeners (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.removeAllListeners)
- description and source-code
```javascript
removeAllListeners = function (event, fn){
  this._callbacks = this._callbacks || {};

  // all
  if (0 == arguments.length) {
    this._callbacks = {};
    return this;
  }

  // specific event
  var callbacks = this._callbacks['$' + event];
  if (!callbacks) return this;

  // remove all handlers
  if (1 == arguments.length) {
    delete this._callbacks['$' + event];
    return this;
  }

  // remove specific handler
  var cb;
  for (var i = 0; i < callbacks.length; i++) {
    cb = callbacks[i];
    if (cb === fn || cb.fn === fn) {
      callbacks.splice(i, 1);
      break;
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.removeEventListener"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>removeEventListener (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.removeEventListener)
- description and source-code
```javascript
removeEventListener = function (event, fn){
  this._callbacks = this._callbacks || {};

  // all
  if (0 == arguments.length) {
    this._callbacks = {};
    return this;
  }

  // specific event
  var callbacks = this._callbacks['$' + event];
  if (!callbacks) return this;

  // remove all handlers
  if (1 == arguments.length) {
    delete this._callbacks['$' + event];
    return this;
  }

  // remove specific handler
  var cb;
  for (var i = 0; i < callbacks.length; i++) {
    cb = callbacks[i];
    if (cb === fn || cb.fn === fn) {
      callbacks.splice(i, 1);
      break;
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.removeListener"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>removeListener (event, fn)](#apidoc.element.socket.io-client.Manager.prototype.removeListener)
- description and source-code
```javascript
removeListener = function (event, fn){
  this._callbacks = this._callbacks || {};

  // all
  if (0 == arguments.length) {
    this._callbacks = {};
    return this;
  }

  // specific event
  var callbacks = this._callbacks['$' + event];
  if (!callbacks) return this;

  // remove all handlers
  if (1 == arguments.length) {
    delete this._callbacks['$' + event];
    return this;
  }

  // remove specific handler
  var cb;
  for (var i = 0; i < callbacks.length; i++) {
    cb = callbacks[i];
    if (cb === fn || cb.fn === fn) {
      callbacks.splice(i, 1);
      break;
    }
  }
  return this;
}
```
- example usage
```shell
...
 * @api public
 */

function on (obj, ev, fn) {
  obj.on(ev, fn);
  return {
    destroy: function () {
      obj.removeListener(ev, fn);
    }
  };
}
...
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.socket"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>socket (nsp, opts)](#apidoc.element.socket.io-client.Manager.prototype.socket)
- description and source-code
```javascript
socket = function (nsp, opts) {
  var socket = this.nsps[nsp];
  if (!socket) {
    socket = new Socket(this, nsp, opts);
    this.nsps[nsp] = socket;
    var self = this;
    socket.on('connecting', onConnecting);
    socket.on('connect', function () {
      socket.id = self.engine.id;
    });

    if (this.autoConnect) {
      // manually call here since connecting evnet is fired before listening
      onConnecting();
    }
  }

  function onConnecting () {
    if (!~indexOf(self.connecting, socket)) {
      self.connecting.push(socket);
    }
  }

  return socket;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.timeout"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>timeout (v)](#apidoc.element.socket.io-client.Manager.prototype.timeout)
- description and source-code
```javascript
timeout = function (v) {
  if (!arguments.length) return this._timeout;
  this._timeout = v;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Manager.prototype.updateSocketIds"></a>[function <span class="apidocSignatureSpan">socket.io-client.Manager.prototype.</span>updateSocketIds ()](#apidoc.element.socket.io-client.Manager.prototype.updateSocketIds)
- description and source-code
```javascript
updateSocketIds = function () {
  for (var nsp in this.nsps) {
    if (has.call(this.nsps, nsp)) {
      this.nsps[nsp].id = this.engine.id;
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socket.io-client.Socket"></a>[module socket.io-client.Socket](#apidoc.module.socket.io-client.Socket)

#### <a name="apidoc.element.socket.io-client.Socket.Socket"></a>[function <span class="apidocSignatureSpan">socket.io-client.</span>Socket (io, nsp, opts)](#apidoc.element.socket.io-client.Socket.Socket)
- description and source-code
```javascript
function Socket(io, nsp, opts) {
  this.io = io;
  this.nsp = nsp;
  this.json = this; // compat
  this.ids = 0;
  this.acks = {};
  this.receiveBuffer = [];
  this.sendBuffer = [];
  this.connected = false;
  this.disconnected = true;
  if (opts && opts.query) {
    this.query = opts.query;
  }
  if (this.io.autoConnect) this.open();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.socket.io-client.Socket.prototype"></a>[module socket.io-client.Socket.prototype](#apidoc.module.socket.io-client.Socket.prototype)

#### <a name="apidoc.element.socket.io-client.Socket.prototype.ack"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>ack (id)](#apidoc.element.socket.io-client.Socket.prototype.ack)
- description and source-code
```javascript
ack = function (id) {
  var self = this;
  var sent = false;
  return function () {
    // prevent double callbacks
    if (sent) return;
    sent = true;
    var args = toArray(arguments);
    debug('sending ack %j', args);

    var type = hasBin(args) ? parser.BINARY_ACK : parser.ACK;
    self.packet({
      type: type,
      id: id,
      data: args
    });
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.addEventListener"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>addEventListener (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.addEventListener)
- description and source-code
```javascript
addEventListener = function (event, fn){
  this._callbacks = this._callbacks || {};
  (this._callbacks['$' + event] = this._callbacks['$' + event] || [])
    .push(fn);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.close"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>close ()](#apidoc.element.socket.io-client.Socket.prototype.close)
- description and source-code
```javascript
close = function () {
  if (this.connected) {
    debug('performing disconnect (%s)', this.nsp);
    this.packet({ type: parser.DISCONNECT });
  }

  // remove socket from pool
  this.destroy();

  if (this.connected) {
    // fire events
    this.onclose('io client disconnect');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.compress"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>compress (compress)](#apidoc.element.socket.io-client.Socket.prototype.compress)
- description and source-code
```javascript
compress = function (compress) {
  this.flags = this.flags || {};
  this.flags.compress = compress;
  return this;
}
```
- example usage
```shell
...

#### Socket#compress(v:Boolean):Socket

Sets a modifier for a subsequent event emission that the event data will
only be _compressed_ if the value is 'true'. Defaults to 'true' when you don't call the method.

'''js
socket.compress(false).emit('an event', { some: 'data' });
'''

#### Events

- 'connect'. Fired upon a connection including a successful reconnection.
- 'error'. Fired upon a connection error
  Parameters:
...
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.connect"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>connect ()](#apidoc.element.socket.io-client.Socket.prototype.connect)
- description and source-code
```javascript
connect = function () {
  if (this.connected) return this;

  this.subEvents();
  this.io.open(); // ensure open
  if ('open' === this.io.readyState) this.onopen();
  this.emit('connecting');
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.destroy"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>destroy ()](#apidoc.element.socket.io-client.Socket.prototype.destroy)
- description and source-code
```javascript
destroy = function () {
  if (this.subs) {
    // clean subscriptions to avoid reconnections
    for (var i = 0; i < this.subs.length; i++) {
      this.subs[i].destroy();
    }
    this.subs = null;
  }

  this.io.destroy(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.disconnect"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>disconnect ()](#apidoc.element.socket.io-client.Socket.prototype.disconnect)
- description and source-code
```javascript
disconnect = function () {
  if (this.connected) {
    debug('performing disconnect (%s)', this.nsp);
    this.packet({ type: parser.DISCONNECT });
  }

  // remove socket from pool
  this.destroy();

  if (this.connected) {
    // fire events
    this.onclose('io client disconnect');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.emit"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>emit (ev)](#apidoc.element.socket.io-client.Socket.prototype.emit)
- description and source-code
```javascript
emit = function (ev) {
  if (events.hasOwnProperty(ev)) {
    emit.apply(this, arguments);
    return this;
  }

  var args = toArray(arguments);
  var parserType = parser.EVENT; // default
  if (hasBin(args)) { parserType = parser.BINARY_EVENT; } // binary
  var packet = { type: parserType, data: args };

  packet.options = {};
  packet.options.compress = !this.flags || false !== this.flags.compress;

  // event ack callback
  if ('function' === typeof args[args.length - 1]) {
    debug('emitting packet with ack id %d', this.ids);
    this.acks[this.ids] = args.pop();
    packet.id = this.ids++;
  }

  if (this.connected) {
    this.packet(packet);
  } else {
    this.sendBuffer.push(packet);
  }

  delete this.flags;

  return this;
}
```
- example usage
```shell
...

#### Socket#compress(v:Boolean):Socket

Sets a modifier for a subsequent event emission that the event data will
only be _compressed_ if the value is 'true'. Defaults to 'true' when you don't call the method.

'''js
socket.compress(false).emit('an event', { some: 'data' });
'''

#### Events

- 'connect'. Fired upon a connection including a successful reconnection.
- 'error'. Fired upon a connection error
  Parameters:
...
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.emitBuffered"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>emitBuffered ()](#apidoc.element.socket.io-client.Socket.prototype.emitBuffered)
- description and source-code
```javascript
emitBuffered = function () {
  var i;
  for (i = 0; i < this.receiveBuffer.length; i++) {
    emit.apply(this, this.receiveBuffer[i]);
  }
  this.receiveBuffer = [];

  for (i = 0; i < this.sendBuffer.length; i++) {
    this.packet(this.sendBuffer[i]);
  }
  this.sendBuffer = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.hasListeners"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>hasListeners (event)](#apidoc.element.socket.io-client.Socket.prototype.hasListeners)
- description and source-code
```javascript
hasListeners = function (event){
  return !! this.listeners(event).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.listeners"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>listeners (event)](#apidoc.element.socket.io-client.Socket.prototype.listeners)
- description and source-code
```javascript
listeners = function (event){
  this._callbacks = this._callbacks || {};
  return this._callbacks['$' + event] || [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.off"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>off (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.off)
- description and source-code
```javascript
off = function (event, fn){
  this._callbacks = this._callbacks || {};

  // all
  if (0 == arguments.length) {
    this._callbacks = {};
    return this;
  }

  // specific event
  var callbacks = this._callbacks['$' + event];
  if (!callbacks) return this;

  // remove all handlers
  if (1 == arguments.length) {
    delete this._callbacks['$' + event];
    return this;
  }

  // remove specific handler
  var cb;
  for (var i = 0; i < callbacks.length; i++) {
    cb = callbacks[i];
    if (cb === fn || cb.fn === fn) {
      callbacks.splice(i, 1);
      break;
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.on"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>on (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.on)
- description and source-code
```javascript
on = function (event, fn){
  this._callbacks = this._callbacks || {};
  (this._callbacks['$' + event] = this._callbacks['$' + event] || [])
    .push(fn);
  return this;
}
```
- example usage
```shell
...
socket.io server as '/socket.io/socket.io.js'. Alternatively you can
serve the file 'socket.io.js' or 'socket.io.min.js' found in the 'dist' folder.

'''html
<script src="/socket.io/socket.io.js"></script>
<script>
  var socket = io('http://localhost');
  socket.on('connect', function(){});
  socket.on('event', function(data){});
  socket.on('disconnect', function(){});
</script>
'''

Socket.IO is compatible with [browserify](http://browserify.org/).
...
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.onack"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onack (packet)](#apidoc.element.socket.io-client.Socket.prototype.onack)
- description and source-code
```javascript
onack = function (packet) {
  var ack = this.acks[packet.id];
  if ('function' === typeof ack) {
    debug('calling ack %s with %j', packet.id, packet.data);
    ack.apply(this, packet.data);
    delete this.acks[packet.id];
  } else {
    debug('bad ack %s', packet.id);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.once"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>once (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.once)
- description and source-code
```javascript
once = function (event, fn){
  function on() {
    this.off(event, on);
    fn.apply(this, arguments);
  }

  on.fn = fn;
  this.on(event, on);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.onclose"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onclose (reason)](#apidoc.element.socket.io-client.Socket.prototype.onclose)
- description and source-code
```javascript
onclose = function (reason) {
  debug('close (%s)', reason);
  this.connected = false;
  this.disconnected = true;
  delete this.id;
  this.emit('disconnect', reason);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.onconnect"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onconnect ()](#apidoc.element.socket.io-client.Socket.prototype.onconnect)
- description and source-code
```javascript
onconnect = function () {
  this.connected = true;
  this.disconnected = false;
  this.emit('connect');
  this.emitBuffered();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.ondisconnect"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>ondisconnect ()](#apidoc.element.socket.io-client.Socket.prototype.ondisconnect)
- description and source-code
```javascript
ondisconnect = function () {
  debug('server disconnect (%s)', this.nsp);
  this.destroy();
  this.onclose('io server disconnect');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.onevent"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onevent (packet)](#apidoc.element.socket.io-client.Socket.prototype.onevent)
- description and source-code
```javascript
onevent = function (packet) {
  var args = packet.data || [];
  debug('emitting event %j', args);

  if (null != packet.id) {
    debug('attaching ack callback to event');
    args.push(this.ack(packet.id));
  }

  if (this.connected) {
    emit.apply(this, args);
  } else {
    this.receiveBuffer.push(args);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.onopen"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onopen ()](#apidoc.element.socket.io-client.Socket.prototype.onopen)
- description and source-code
```javascript
onopen = function () {
  debug('transport is open - connecting');

  // write connect packet if necessary
  if ('/' !== this.nsp) {
    if (this.query) {
      this.packet({type: parser.CONNECT, query: this.query});
    } else {
      this.packet({type: parser.CONNECT});
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.onpacket"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>onpacket (packet)](#apidoc.element.socket.io-client.Socket.prototype.onpacket)
- description and source-code
```javascript
onpacket = function (packet) {
  if (packet.nsp !== this.nsp) return;

  switch (packet.type) {
    case parser.CONNECT:
      this.onconnect();
      break;

    case parser.EVENT:
      this.onevent(packet);
      break;

    case parser.BINARY_EVENT:
      this.onevent(packet);
      break;

    case parser.ACK:
      this.onack(packet);
      break;

    case parser.BINARY_ACK:
      this.onack(packet);
      break;

    case parser.DISCONNECT:
      this.ondisconnect();
      break;

    case parser.ERROR:
      this.emit('error', packet.data);
      break;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.open"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>open ()](#apidoc.element.socket.io-client.Socket.prototype.open)
- description and source-code
```javascript
open = function () {
  if (this.connected) return this;

  this.subEvents();
  this.io.open(); // ensure open
  if ('open' === this.io.readyState) this.onopen();
  this.emit('connecting');
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.packet"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>packet (packet)](#apidoc.element.socket.io-client.Socket.prototype.packet)
- description and source-code
```javascript
packet = function (packet) {
  packet.nsp = this.nsp;
  this.io.packet(packet);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>removeAllListeners (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.removeAllListeners)
- description and source-code
```javascript
removeAllListeners = function (event, fn){
  this._callbacks = this._callbacks || {};

  // all
  if (0 == arguments.length) {
    this._callbacks = {};
    return this;
  }

  // specific event
  var callbacks = this._callbacks['$' + event];
  if (!callbacks) return this;

  // remove all handlers
  if (1 == arguments.length) {
    delete this._callbacks['$' + event];
    return this;
  }

  // remove specific handler
  var cb;
  for (var i = 0; i < callbacks.length; i++) {
    cb = callbacks[i];
    if (cb === fn || cb.fn === fn) {
      callbacks.splice(i, 1);
      break;
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.removeEventListener"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>removeEventListener (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.removeEventListener)
- description and source-code
```javascript
removeEventListener = function (event, fn){
  this._callbacks = this._callbacks || {};

  // all
  if (0 == arguments.length) {
    this._callbacks = {};
    return this;
  }

  // specific event
  var callbacks = this._callbacks['$' + event];
  if (!callbacks) return this;

  // remove all handlers
  if (1 == arguments.length) {
    delete this._callbacks['$' + event];
    return this;
  }

  // remove specific handler
  var cb;
  for (var i = 0; i < callbacks.length; i++) {
    cb = callbacks[i];
    if (cb === fn || cb.fn === fn) {
      callbacks.splice(i, 1);
      break;
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.removeListener"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>removeListener (event, fn)](#apidoc.element.socket.io-client.Socket.prototype.removeListener)
- description and source-code
```javascript
removeListener = function (event, fn){
  this._callbacks = this._callbacks || {};

  // all
  if (0 == arguments.length) {
    this._callbacks = {};
    return this;
  }

  // specific event
  var callbacks = this._callbacks['$' + event];
  if (!callbacks) return this;

  // remove all handlers
  if (1 == arguments.length) {
    delete this._callbacks['$' + event];
    return this;
  }

  // remove specific handler
  var cb;
  for (var i = 0; i < callbacks.length; i++) {
    cb = callbacks[i];
    if (cb === fn || cb.fn === fn) {
      callbacks.splice(i, 1);
      break;
    }
  }
  return this;
}
```
- example usage
```shell
...
 * @api public
 */

function on (obj, ev, fn) {
  obj.on(ev, fn);
  return {
    destroy: function () {
      obj.removeListener(ev, fn);
    }
  };
}
...
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.send"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>send ()](#apidoc.element.socket.io-client.Socket.prototype.send)
- description and source-code
```javascript
send = function () {
  var args = toArray(arguments);
  args.unshift('message');
  this.emit.apply(this, args);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.socket.io-client.Socket.prototype.subEvents"></a>[function <span class="apidocSignatureSpan">socket.io-client.Socket.prototype.</span>subEvents ()](#apidoc.element.socket.io-client.Socket.prototype.subEvents)
- description and source-code
```javascript
subEvents = function () {
  if (this.subs) return;

  var io = this.io;
  this.subs = [
    on(io, 'open', bind(this, 'onopen')),
    on(io, 'packet', bind(this, 'onpacket')),
    on(io, 'close', bind(this, 'onclose'))
  ];
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
