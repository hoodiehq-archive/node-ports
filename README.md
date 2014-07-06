# Ports registry
[![Build Status](https://travis-ci.org/hoodiehq/node-ports.svg)](https://travis-ci.org/hoodiehq/node-ports)
[![Dependency Status](https://david-dm.org/hoodiehq/node-ports.svg)](https://david-dm.org/hoodiehq/node-ports)
[![devDependency Status](https://david-dm.org/hoodiehq/node-ports/dev-status.svg)](https://david-dm.org/hoodiehq/node-ports#info=devDependencies)

Manage a registry of unique port assignments for
an operating system. Store user-defined meta-data
with each port.

The registry lives in ~/.ports

Note that this module currently doesn’t check whether
a port is actually available. That’s TBD.


## I want my app to register itself with ports!
```js
var ports = require("ports");
ports.getPort("yourfancyproject");
```

## License

Apache 2 License


## Copyright

(c) 2013 Jan Lehnardt <jan@apache.org>
