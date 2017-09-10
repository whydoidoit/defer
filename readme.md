### Introduction

Defer for Bluebird promises (sorry, really did need them).

### Installation

```language-shell
npm install --save bluebird-defer-polyfill
```

### Usage

```language-javascript
import Defer from 'bluebird-defer-polyfill'
let defer = new Defer();

if(x) defer.resolve(x) else defer.reject(new Error("OOps"));

...

return defer.promise

```

### Requirements

Uses ES6/Babel/PlayCanvas template. ES6 format module.
