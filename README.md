# node-newrelic wrapper

This package allows you to initialize newrelic without creating a newrelic.js file. Simply do the following:

`npm i better-newrelic`

```js
var newrelic = require('better-newrelic')({
  app_name: ['my-appname'],
  license_key: '123456789'
})

// newrelic is the original object, see original docs for details
```

see docs at [https://www.npmjs.com/package/newrelic](https://www.npmjs.com/package/newrelic)
