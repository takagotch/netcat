### netcat
---
https://github.com/roccomuso/netcat

```js
// tests/tcp.js
'use strict'

const test = require('tape')

test('Client and Server constructor', function (t) {
  t.plan(2)
  
  try {
    var nc = new NetcatServer()
    var nc2 = new NetcatClient()
    t.ok(nc, 'Server constructor')
    t.ok(nc2, 'Client constructor')
  } catch (e) {
    t.fail(e)
  }
})



```

```
```

```
```


