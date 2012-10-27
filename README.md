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


2012 by Tim Pietrusky

[timpietrusky.com](http://timpietrusky.com)