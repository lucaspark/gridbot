Gridbot
=========

###The obedient grid system.###


---
Gridbot is (yet) another grid, with the advantage of being extremely lightweight, easy-to-use, with allowance of different grid sizes for mobile browser widths (as opposed to 100% width for any and all content). 


Visit the [GridBot] page for more detail information as well as exmamples; however, a basic structure is below: 

---

```
<div class="group">
    <div class="d12 m6"><!--Content--></div>
</div>
```
The ```d``` class represents the desktop width of the content. The default number for the grid is 12, so in this case, the grid will be full-width on browsers wide enough to be considered "desktop" size (This size and associated mobile breakpoint can be changed).

The ```m``` class represents how wide the content will be at mobile widths. In this case, the content will be half the width of the browser. __The ```m``` must always be accompanied by the ```d``` class. If no ```m``` class is present, the grid will default to 100% width in mobile views.__

---

Contents
----
* __CSS__ file (Defaults: 12 Grid, 2% Gutter, 1200px max width, 768px break point)
* __Minified CSS__ File (1 kb)
* __SCSS__ file (edited with SASS)

With the SCSS file, you can change settings like __break points__, __max width__ of content, __number of grid units__, and the __gutter__.



License
----

MIT




[GridBot]:http://lucaspark.github.io/gridbot/
