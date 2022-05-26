---
# Configurations
# black, white, league, beige, sky, simple, serif, night, moon, solarized
theme: night
# cube, page, concave, zoom, linear, fade, none, default 
transition: slide
#  Syntax highlighting style https://highlightjs.org/static/demo/
highlight: solarized-dark
backgroundTransition: zoom
progress: true
controls: true
hideAddressBar: true

# Editor settings
editor:
    fontSize: 14
    theme: solarized_light
    # keybinding: vim
---
# MarkShow 
## Markdown to Slideshow

Powered by Reveal.js 


#### feedback is welcomed at
<a href="http://twitter.com/motyar" target="_blank" data-preview-link="false" >@motyar</a> on Twitter

---
# Custom styling
You also can override the theme style, check any [theme source](https://mark.show/reveal.js@4.0.2/dist/theme/simple.css) for more info

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@800&display=swap');
.slide { color:#116466; background: #2c3531;}
.slide h1{ color: #ffcb9a; font-family: 'Playfair Display', serif; }
.reveal p { color: #d1e8e2;}
.reveal li{ color: #d1e8e2;}
.reveal a { color: #89b08c; }
.reveal .controls { color: #0a97b0; }
.reveal .progress { color: #1b6ca8; }
</style>

---

# How

- Write your presentation as Markdown text
- Click on slide area to play
- Press E to edit again

---
# features 

### Select a markdown slide file from your computer.
<input accept=".txt,.md" type="file">                                              

---
# Or
### Drag and Drop a markdown slide file anywhere on this webpage.
---
# Or

### Import from external source    
Append **mark.show/** to source file url 

 Example [https://mark.show/DOMAIN.TLD/PATH/FILE_NAME.md](https://mark.show/gist.githubusercontent.com/motyar/16fb4aa3eca6f91abd46d5a4349f725d/raw/d3b264e5e66622b26be39397adc0b3925297fc15/slide.md)

---

### How to use Markdown to make beautiful presentations

Start a new slide with line break, three dashes, and another linebreak
---
# Keyboard Shortcuts
### Press **?** when presenting. 

---
## Speaker View

This can be used to present per-slide notes in a separate browser window. The notes window also gives you a preview of the next upcoming slide so it may be helpful even if you haven't written any notes. 

**Press the S key** when presenting to open the notes window.

A speaker timer starts as soon as the speaker view is opened. You can reset the timer by clicking on it.

Note:
This will only display in the notes window.
---

### You can include inspirational quotes

>You miss 100 percent of the shots you never take. ~Wayne Gretzky

---

# Use tables 

| Tables        | Are           | Cool  | 
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 | 

---
## Auto animate

From this

<!-- .slide: data-auto-animate -->
  <div data-id="box" style="height: 50px; background: yellow;"></div>
---
## Auto animated
To this
<!-- .slide: data-auto-animate -->
  <div data-id="box" style="height: 100px; background: pink;"></div>
 
---
<!-- .slide: data-auto-animate -->

## Automatically animate matching elements across slides
<div class="r-hstack justify-center"><div data-id="box1" style="background: #999; width: 50px; height: 50px; margin: 10px; border-radius: 5px;" data-auto-animate-target=""></div><div data-id="box2" style="background: #999; width: 50px; height: 50px; margin: 10px; border-radius: 5px;" data-auto-animate-target=""></div><div data-id="box3" style="background: #999; width: 50px; height: 50px; margin: 10px; border-radius: 5px;" data-auto-animate-target=""></div></div>
---
<!-- .slide: data-auto-animate -->

<div class="r-hstack justify-center">
<div data-id="box1" data-auto-animate-delay="0" style="background: cyan; width: 150px; height: 100px; margin: 10px;" data-auto-animate-target="51"></div>
<div data-id="box2" data-auto-animate-delay="0.1" style="background: magenta; width: 150px; height: 100px; margin: 10px;" data-auto-animate-target="52"></div>
<div data-id="box3" data-auto-animate-delay="0.2" style="background: yellow; width: 150px; height: 100px; margin: 10px;" data-auto-animate-target="53"></div>
</div>

---
<!-- .slide: data-auto-animate -->
<div class="r-stack">
<div data-id="box1" style="background: cyan; width: 300px; height: 300px; border-radius: 200px;" data-auto-animate-target="55"></div>
<div data-id="box2" style="background: magenta; width: 200px; height: 200px; border-radius: 200px;" data-auto-animate-target="56"></div>
<div data-id="box3" style="background: yellow; width: 100px; height: 100px; border-radius: 200px;" data-auto-animate-target="57"></div>
</div>

---

# Use Images

![Sample image](https://source.unsplash.com/600x300/?pink)

---
<!-- .slide: data-background="pink" -->
# Slide attributes 
## Data background

---
<!-- .slide: data-background="https://source.unsplash.com/600x600/?smile"  --> 

# Image as slide backgroud

---
<!-- .slide: data-background="https://i.giphy.com/90F8aUepslB84.gif" -->
# ... and GIFs!

---

## data-transitions
in this slide we are using "convex-in fade-out"
<!-- .slide: data-transition="convex-in fade-out" data-background="#234" -->

---
<!-- .slide: data-transition="zoom-in zoom-out" -->
## data-transition "zoom-in zoom-out" 
try none/fade/slide/convex/concave/zoom

---
 ## Element attributes fragment
- Item 1 <!-- .element: class="fragment " data-fragment-index="2" -->
- Item 2 <!-- .element: class="fragment " data-fragment-index="1" -->

---

<!-- .slide: data-transition="zoom-in zoom-out" data-transition-speed="slow"-->
### data-transition-speed
Slow or Fast
 
---

# Emojis

# 😍


---

1. Ordered list
1. Use a 1 on every line
1. And they will be given the correct sequence

..................................

- Unordered list
* Use any of these three characters
+ And you will get a bulleted list

---


You **embolden** text like this or __like this__
You *emphasize* text like this or _like this_
Or __*do both*__ at the same time
You can also ~~strikethrough~~ text

---

# Heading 1
## Heading 2
### Heading 3
#### Heading 4

---


### Syntax highlighted code — powered by highlight.js
 Supports all [HighLightJs](https://highlightjs.org)'s 189 languages and 94 styles.

```js
var docCookies = new Proxy(docCookies, {
  get: function (oTarget, sKey) {
    return oTarget[sKey] || oTarget.getItem(sKey) || undefined;
  },
  set: function (oTarget, sKey, vValue) {
    if (sKey in oTarget) { return false; }
    return oTarget.setItem(sKey, vValue);
  },
  defineProperty: function (oTarget, sKey, oDesc) {
    if (oDesc && "value" in oDesc) { oTarget.setItem(sKey, oDesc.value); }
    return oTarget;
  },
  getOwnPropertyDescriptor: function (oTarget, sKey) {
    var vValue = oTarget.getItem(sKey);
    return vValue ? {
      value: vValue,
      writable: true,
      enumerable: true,
      configurable: false
    } : undefined;
  },
});
```
---

### Support for math using LaTeX

<h2>The Lorenz Equations</h2>
  \[\begin{aligned}
  \dot{x} &amp; = \sigma(y-x) \\
  \dot{y} &amp; = \rho x - y - xz \\
  \dot{z} &amp; = -\beta z + xy
  \end{aligned} \]

---

# Feedback is welcomed
Reach us at  <a href="http://twitter.com/motyar" target="_blank" data-preview-link="false" >@motyar</a> on Twitter
