# crystallo

![crystallo](https://raw.github.com/TimPietrusky/crystallo/master/img/crystallo_big.png)

it's ultra responsive to be a responsive css framework.

## What?
crystallo is a solid & simple **responsive micro framework** to help you **kick-start** any form of **web creation**.

This is the **alpha** release and it would be awesome if **you** could **help**: critique, bugs, ideas!

## Features!

* clean & semantic HTML
* class / id free
* up to 5 fluid columns
* buttons
* vertical-align: center
* theme support
* and what ever you want!

## In the not so far future...

* image
* form
* navigation
* table
* theme skeleton / creator

## How to

### 1. Add the css & prefixfree

```html
<head>
    <link rel="stylesheet" href="css/crystallo.css">
    <link rel="stylesheet" href="css/theme/minimal.css">
    <script src="http://raw.github.com/LeaVerou/prefixfree/gh-pages/prefixfree.min.js"></script>
</head>
```

### 2. Define a max-width, theme or auto-extend if you like

```html
<body data-max-width="1400" data-theme="minimal" data-auto-extend="true">
```

## The core has no styles

So you can take advantage of the core functionality and create your own ultra custom theme.

There are just three predefined attributes, which affect the whole body.


### data-max-width (px)

* none [default]
* 860
* 1024
* 1152
* 1280
* 1400
* 1600
* 2048
* 3200
* 4000


### data-theme

The core has no style, so we need themes! Right?

* none [default]
* minimal
* your custom theme here?


### data-auto-extend

Even if data-max-width is specified, auto extend the body to the next size.

* false [default]
* true

```html
<body data-max-width="1400" data-theme="minimal" data-auto-extend="true">
</body>
```

## up to 5 shiny columns

This is all you need to keep focus on the content and not on pixel perfect designs.

### 1 column

```html
<article data-high="1" data-text="1 column">
  <section data-cols="1" data-valign="center">
    <div>
      <h2>column 1</h2>
    </div>
  </section>
</article>
```

### 2 columns  
```html
<article data-high="2" data-text="2 columns">
  <section data-cols="2" data-valign="center">
    <div>
      <h2>column 1</h2>
    </div>
    <div>
      <h2>column 2</h2>
    </div>
  </section>
</article>
```

### 3 columns  
```html
<article data-high="3" data-text="3 columns">
  <section data-cols="3" data-valign="center">
    <div>
      <h2>column 1</h2>
    </div>
    <div>
      <h2>column 2</h2>
    </div>
    <div>
      <h2>column 3</h2>
    </div>
  </section>
</article>
```

### 4 columns  
```html
<article data-high="4" data-text="4 columns">
  <section data-cols="4" data-valign="center">
    <div>
      <h2>column 1</h2>
    </div>
    <div>
      <h2>column 2</h2>
    </div>
    <div>
      <h2>column 3</h2>
    </div>
    <div>
      <h2>column 4</h2>
    </div>
  </section>
</article>
```
        
### 5 columns    
```html
<article data-high="5" data-text="5 columns">
  <section data-cols="5" data-valign="center">
    <div>
      <h2>column 1</h2>
    </div>
    <div>
      <h2>column 2</h2>
    </div>
    <div>
      <h2>column 3</h2>
    </div>
    <div>
      <h2>column 4</h2>
    </div>
    <div>
      <h2>column 5</h2>
    </div>
  </section>
</article>
```

### Buttons

```html
<section data-cols="1" data-valign="center">
  <div>
    <button>default/button>
  </div>
</section>
<section data-cols="5" data-valign="center">
  <div>
    <button data-high="1">high 1</button>
  </div>
  <div>
    <button data-high="1">high 2</button>
  </div>
  <div>
    <button data-high="1">high 3</button>
  </div>
  <div>
    <button data-high="1">high 4</button>
  </div>
  <div>
    <button data-high="1">high 5</button>
  </div>
</section>
```


2012 by Tim Pietrusky

[timpietrusky.com](http://timpietrusky.com)