# jQuery Directional Hover

A jQuery plugin that slides overlays over elements based on mouse direction

Currently version 1.0.1

## Installation

This plugin is available via [npm](https://www.npmjs.com/) (`npm install jquery-directional-hover`) and [bower](http://bower.io/) (`bower install jquery-directional-hover`). Or, you can just download it from this repo.

## Usage

Create a container element with an overlay element inside:

```html
<div class="dh-container">
	<div class="dh-overlay"></div>
</div>
```

Call the directional hover plugin on your container element:

```js
$('.dh-container').directionalHover();
```

That's it! There are additional options you can use for the plugin.

## Options

You can either modify the `$.fn.directionalHover.defaults` object or pass a new object into the `.directionalHover()` function.

### overlay

The jQuery selector of the overlay in the container element.

**Type:** `String`

**Default:** `.dh-overlay`

### easing

The jQuery easing function the overlay will use.

**Type:** `String`

**Default:** `swing`

### speed

The speed in milliseconds at which the overlay will slide in and out at.

**Type:** `Number`

**Default:** `400`

## API

Coming soon...