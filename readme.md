##desc
    redefine console in node
    
    [模块名 : 行号] 信息 [距离初始用时] [距离上次log用时]

![url](http://ofky9kljx.bkt.clouddn.com/2016-10-25_095542.png)

##usage

```javascript
var console = require('sfconsole')("Module");
//var console = require('sfconsole')("Module", false);
//var console = require('sfconsole')();

console.log('log...');
console.warn('warn...');
console.err('err...');
console.info('logs...');
console._log('原始console.log');
```