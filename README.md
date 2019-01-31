### transitionEnd
---
https://github.com/EvandroLG/transitionEnd

```
npm install transitionEnd
bower install transitionEnd
```

```js
var box = $("#box");
var foo = $("#foo");
transitionEnd(box).bind(function(){
  foo.addClass("on");
  transitionEnd(box).unbind();
});
var transition = transitionEnd(box).whichTransitionEnd();

```

```
```

