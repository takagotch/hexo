### hexo
---
https://github.com/hexojs/hexo

```
npm install hexo-cli -g

hexo init blog
hexo server
hexo new "Hello"
hexo generate
npm install 
hexo server

```

```js
var Hexo = require('hexo');
var hexo = new Hexo(process.cwd(), {});

hexo.init().then(function(){
});

hexo.load().then(function(){
});

hexo.watch().then(funciton(){
});

hexo.call('generate', {}).then(function(){
});

hexo.call('list', { _: ['post'] }).then(function() {
})

hexo.call('generate').then(function(){
  return hexo.exit();
}).catch(function(err){
  return hexo.exit(err);
});


```

```
```


