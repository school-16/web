So what is CSS, really?
=======================

Like HTML, CSS is not really a programming language. It is not a markup language either — it is a style sheet language. This means that it lets you apply styles selectively to elements in HTML documents. For example, to select all the paragraph elements on an HTML page and turn the text within them red, you'd write this CSS:

```css
p {
  color: red;
}
```

Getting started
---------------

1. Open your index.html file and paste the following line somewhere in the head (that is, between the `<head>` and `</head>` tags):
```html
<link href="styles/style.css" rel="stylesheet" type="text/css">
```
2. Save index.html and load it in your browser.

![Anatomy of a CSS ruleset](/images/img-2.png)

* `font-family`
* `font-weight`
* `font-size`
* `color`

* `margin` (`maring-top`, `maring-right`, `maring-bottom`, `maring-left`)
* `padding` (`padding-top`, `padding-right`, `padding-bottom`, `padding-left`)

* `background`


* html: `<p class="ClassName"></p>` css: `.ClassName { ... }`
* html: `<p id="IdName"></p>` css: `#IdName { ... }`