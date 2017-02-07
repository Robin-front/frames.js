
> 根据张鑫旭的 requestAnimationFrame 和 tween.js 稍作改动

### usage

```
var a = function(){
    tick(a, rate);
  }
  a();
```
给 frames 加rate参数是为了可以自主调节帧率, 当然， 帧率不等于60的时候，会使用 setTimeout.

### tween.js

拓展了 Math 对象。
