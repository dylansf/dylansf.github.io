# Layout

## To Do

## Feature List
* Use ```<div>``` and ```<span>``` to create blocks
* Position parts of a webpage with float
* Position parts of a webpage with flex

## Creating Blocks with ```<div>``` and ```<span>```

We will now learn to create content blocks. Content blocks don't directly change the way a webpage looks, instead they create content containers that we can modify using CSS.
To explore our ```<div>``` element we will create a div on a new [Codepen](codepen.io). 
```html
<iframe height="265" scrolling="no" title="CSS Layout" src="//codepen.io/instructionalist/embed/YjrBJX/?height=265&theme-id=0&default-tab=css,result&embed-version=2&editable=true" frameborder="no" allowtransparency="true" allowfullscreen="true" style="width: 100%;"></iframe>
```
```html
<iframe height="469" scrolling="no" title="CSS Layout" src="//codepen.io/instructionalist/embed/YjrBJX/?height=469&theme-id=0&default-tab=css,result&embed-version=2&editable=true" frameborder="no" allowtransparency="true" allowfullscreen="true" style="width: 100%;">See the Pen <a href="https://codepen.io/instructionalist/pen/YjrBJX/">CSS Layout</a> by Dylan Miracle (<a href="https://codepen.io/instructionalist">@instructionalist</a>) on <a href="https://codepen.io">CodePen</a>.
</iframe>
```
```html
http://codepen.io/api/oembed?url=https://codepen.io/instructionalist/pen/YjEKby
```
Add this HTML. This will create two divs that will have the style of two classes. The first is in class red, and class box.

### HTML
```html
<div class="red box"></div>
<div class="blue box"></div>
```
### CSS
```css
.box{
  height: 100px;
  width: 100px;
}
.red {
  background: red;
}
.blue {
  background: blue;
}
```
1. Create divs called red, green, and blue
2. Style red, green and blue
    * make 100 px tall
    * set background color
    



## Float
Float takes elements out of normal document flow and moves them around. This is a good way to get text to go around pictures and position columns. Let's work an example in codepen using the colored boxes we created in the last lesson. Check that you have HTML and CSS as shown in the image below.

```css
.box {
  height: 100px;
  width: 100px;
  float: left;
}
```
For each of the following images, find the CSS to generate that box arrangement.
1. 
```css
.box {
  height: 100px;
  width: 100px;
  float: left;
}
.red {
  background: red;
}
.blue {
  background: blue;
}
.green {
  background: green;
}
```
2.
```css
.box {
  height: 100px;
  width: 100px;
}
.red {
  background: red;
  float: left;
}
.blue {
  background: blue;
  float: right;
}
.green {
  background: green;
  float: left;
}
```
3.
```css
.box {
  height: 100px;
  width: 100px;
}
.red {
  background: red;
  float: right;
}
.blue {
  background: blue;
  float: right;
}
.green {
  background: green;
  float: left;
}
```
### Add image wrapping text here.
### Add Multi-Column practice here.
```html
<iframe scrolling="no" title="Clearing Floats" src="https://codepen.io/instructionalist/embed/pZLXOr/?height=265&theme-id=0&default-tab=html,result&embed-version=2" frameborder="no" allowtransparency="true" allowfullscreen="true" style="width: 100%;"></iframe>
```

