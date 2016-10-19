# get-port-sync
a synchronous version of [sindresorhus/get-port](https://github.com/sindresorhus/get-port)

---
## Install
```
npm install get-port-sync
```


---
## Usage
```
const getPortSync = require('get-port-sync');
let   freePort    = null;

try       { freePort = getPortSync() }
catch (e) { // boo                   }
```


---
## Related
* [sindresorhus/get-port](https://github.com/sindresorhus/get-port)     --> the original get-port module
* [sindresorhus/get-port](https://github.com/sindresorhus/get-port-cli) --> cli for the original get-port module




