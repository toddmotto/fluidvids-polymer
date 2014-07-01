# <fluid-vids>

<fluid-vids> is a web component built on Polymer.js that provides a fluid solution for video embeds.

> [Live demo of <fluid-vids>](http://toddmotto.com/labs/fluidvids-polymer).

See the original [fluidvids](//github.com/toddmotto/fluidvids).

<fluid-vids> has a default ratio of `16:9`, so you can omit the `width` and `height` attributes if your video follows suit.

## Usage

1. Include platform.js and polymer.js:

```html
<script src="lib/platform.js"></script>
<link rel="import" href="bower_components/polymer/polymer.html">
```

2. Import Custom Element:

```html
<link rel="import" href="fluid-vids.html">
```

3. Start using it!

```html
<fluid-vids src="http://www.youtube.com/embed/JMl8cQjBfqk"></fluid-vids>
<fluid-vids src="http://player.vimeo.com/video/23919731" width="800" height="450"></fluid-vids>
```

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style.

## Release history
- 1.0.0
  - Initial release
