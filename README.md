# &lt;fluid-vids&gt;

&lt;fluid-vids&gt; is a web component built on Polymer.js that provides a fluid solution for video embeds.

> [Live demo of &lt;fluid-vids&gt;](http://toddmotto.com/labs/fluidvids-polymer).

See the original [fluidvids](//github.com/toddmotto/fluidvids).

&lt;fluid-vids&gt; has a default ratio of `16:9`, so you can omit the `width` and `height` attributes if your video follows suit.

## Usage

Include platform.js and polymer.js:

```html
<script src="lib/platform.js"></script>
<link rel="import" href="bower_components/polymer/polymer.html">
```

Import Custom Element:

```html
<link rel="import" href="fluid-vids.html">
```

Start using it!

```html
<fluid-vids src="http://www.youtube.com/embed/JMl8cQjBfqk"></fluid-vids>
<fluid-vids src="http://player.vimeo.com/video/23919731" width="800" height="450"></fluid-vids>
```

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style.

## Release history
- 1.0.0
  - Initial release
