# urls
## homepage
[https://code.insistime.com/qiao.util.json](https://code.insistime.com/qiao.util.json)

## github
[https://github.com/insistime/qiao.util.json](https://github.com/insistime/qiao.util.json)

## npm
[https://www.npmjs.com/package/qiao.util.json](https://www.npmjs.com/package/qiao.util.json)

## donate
[http://uikoo9.com/donate](http://uikoo9.com/donate)

# started
## install
npm install qiao.util.json

# api
## json
```javascript
'use strict';

var qiaoUtilJson = require('qiao.util.json');

var json = qiaoUtilJson.json('success', 'test', {});
console.log(json);
```

## success
```javascript
'use strict';

var qiaoUtilJson = require('qiao.util.json');

var success = qiaoUtilJson.success('test', {});
console.log(success);
```

## info
```javascript
'use strict';

var qiaoUtilJson = require('qiao.util.json');

var info = qiaoUtilJson.info('test', {});
console.log(info);
```

## warning
```javascript
'use strict';

var qiaoUtilJson = require('qiao.util.json');

var warning = qiaoUtilJson.warning('test', {});
console.log(warning);
```

## danger
```javascript
'use strict';

var qiaoUtilJson = require('qiao.util.json');

var danger = qiaoUtilJson.danger('test', {});
console.log(danger);
```

# version
## 0.0.3.20181127
1. add .js

## 0.0.2.20181122
1. npm audit

## 0.0.1.20181113
1. init
