---
title: |-
    #JavaScript30 DAY 3
subtitle: 7 takeaways to improve your JavaScript skills 
date: 2017-01-31 00:00:00 Z
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

## Thing \#3: Playing with CSS Variables and JS

![Real-time image styling](/img/css-variables.png)
*Real-time image styling achieved by updating CSS Variables with JavaScript!*

In this particular ***#JavaScript30*** nutritional nugget Wes demonstrates CSS variables and how they work.

**The build:** an image that can be styled in real-time using author-created CSS variables *base*, *spacing*, and *blur*:

```css
<style>
    :root {
    --base: #ffc600;
    --spacing: 10px;
    --blur: 10px;
}

img {
    background: var(--base);
    padding: var(--spacing);
    filter: blur(var(--blur);
}

...

</style>
```

Pretty awesome.

My takeaways.

1. CSS can do some powerful s***!

2. Technically CSS Variables are <a href="https://drafts.csswg.org/css-variables/#defining-variables" target="_blank">*CSS Custom Properties*</a> because they work like regular CSS properties.

3. CSS Variables are declared once. Then, everywhere on the page where those variables are referenced, those instances will self-update. They are dynamic -- no need for a global search and replace to update changed values.

4. CSS preprocessors are static -- variables are defined at compile time, and then cannot be changed at runtime.

5. Declaring a CSS variable on `:root` is essentially the same as declaring it on `html`.

6. CSS Variables inherit from their parent element if no value is set.

7. BADASS (`#B4D455`) is a colour: ![#b4d455](http://placehold.it/15/b4d455/000000?text=+)


#### USEFUL LINKS

- MDN's <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables" target="_blank">*Using CSS Variables*</a><br>
- <a href="https://philipwalton.com/articles/why-im-excited-about-native-css-variables/" target="_blank">*Why I'm Excited About Native CSS Variables*</a> - A blog post by <a href="https://twitter.com/philwalton" target="_blank">Philip Waton</a><br>
- <a href="https://www.youtube.com/watch?v=2an6-WVPuJU" target="_blank">*Lea Verou - CSS Variables: var(--subtitle);*</a> - A talk by <a href="https://twitter.com/LeaVerou" target="_blank">*Lea Verou*</a>  



*[#javascript30](http://javascript30.com) if your interested.*




