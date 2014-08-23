# Browser.css

This provides the SCSS, or CSS, necessary to beautifully present web pages in a browser window.

Typically, this consists of placing screenshots in browser windows, phones, etc. with photo 
editing software. However, I like to avoid Photoshop like the plague, so I concocted a 
CSS/HTML solution.

## Installation

You can directly grab either the SCSS (`scss/`) or CSS (`css/`) directly from this repo.

### NPM Installation

```
$ npm install browser.css --save-dev
```

### Development

For development, there's a gulpfile that compiles the SCSS into CSS. It can be run with:

```
$ gulp
```

If you haven't used Gulp before, try 
[this blog post](http://johnotander.com/front-end-development/2014/08/08/build-tasks-with-gulpjs/).

## Usage

### SCSS

Import the SCSS into your project:

```scss
@import "path/to/browser";
```

### CSS

Link the CSS in your HTML document:

```html
<link rel="stylesheet" href="path/to/browser.min.css">
```

### Example HTML for the browser window:

```html
<div class='browser-window'>
  <div class='top-bar'>
    <div class='circles'>
       <div class="circle circle-red"></div>
       <div class="circle circle-yellow"></div>
       <div class="circle circle-green"></div>
    </div>
  </div>
  <div class='content'>
    <!-- Where the browser content goes. -->
  </div>
</div>
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by [John Otander](http://johnotander.com) ([@4lpine](https://twitter.com/4lpine)).
