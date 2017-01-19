---
title: |-
    #JavaScript30 DAY 1
subtitle: 7 takeaways to improve your JavaScript skills 
date: 2017-01-17 00:00:00 Z
tags:
- css
- javascript
- javascript30
- vanilla-javascript
- wes-bos
- coding-challenge
author: Stan
header-img: img/javascript30-bg.jpg
---

## Thing \#1: JavaScript Drum Kit
*Maps specific keys with sounds to make a keyboard drum kit!*

![JavaScript Drum Kit](/img/js-drumkit.png)

I'm so happy to have come across <a href="https://javascript30.com/" target="_blank">#JavaScript30</a> by <a href="http://wesbos.com/">Wes Bos</a>. What a great way to learn!

Ok, so here are my 7 takeaways.

1. Code a little, test a little, code a little, test little.
2. *console.log()* is your friend. Use it.
3. Consider using <a href="https://developer.mozilla.org/en-US/docs/Web/API/Element/classList" target="_blank">*classList*</a> instead of <a href="https://developer.mozilla.org/en-US/docs/Web/API/Element/className" target="_blank">*className*</a>. Then there is no need to use *split()*. And apparently it is more <a href="https://jsperf.com/classlist-firstclass-vs-classname-firstclass">performant</a>.
4. `addEventListener()` will not work on a <a href="(https://developer.mozilla.org/en-US/docs/Web/API/NodeList">*NodeList*</a>. Each event must be listened to one at a time. Use <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach">`forEach()`</a>.
5. The <a href="https://developer.mozilla.org/en-US/docs/Web/Events/transitionend">`transitionend`</a> event is useful to keep timings in sync. It's a better option in terms maintainability. This way transition times don't need to be maintained in both the .css *and* .js files. The <a href="https://developer.mozilla.org/en-US/docs/Web/Events/animationend">`animationend`</a> event also exists.
6. Learn by doing. Build fun stuff!
7. <a href="https://twitter.com/wesbos">@wesbos</a> is an excellent teacher. Learn from him.