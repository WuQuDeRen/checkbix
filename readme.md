# Checkbix

[![Build Status](https://travis-ci.org/urre/checkbix.svg?branch=master)](https://travis-ci.org/urre/checkbix) ![](https://badge-size.herokuapp.com/urre/checkbix/master/dist/js/checkbix.min.js.svg)

Simple styling for checkboxes. Wip.

## Usage

### Include files

```html
<link rel="stylesheet" href="dist/css/checkbix.min.css">
```

```html
<script src="dist/js/checkbix.min.js"></script>
```

#### Init

```html
<script>
    Checkbix.init();
</script>
```

### Default

```html
<input id="mycheckbox" type="checkbox" class="checkbix" data-text="Checkbix">
```

### Size

```html
<input id="myothercheckbox" type="checkbox" class="checkbix" data-text="Checkbix. Large, checked" data-size="large" checked>
```

## Dev

Build

    npm run build:all    

Watch

    npm run watch:all

Serve
    
    npm run serve

### Todo
+ [ ] Options for circled, colors etc
