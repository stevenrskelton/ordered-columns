&lt;ordered-columns&gt;
================

Polymer Web Component that builds vertically ordered columns (timelines) from arbitrary DOM content.
Unlike CSS columns, earlier content is always rendered closer to the top of the page than later content.

Both the number of columns and column widths can be preconfigured or changed dynamically using Javascript and window resize events, ensuring elements are always rendered in the correct vertical order.

Unlike other other grid layout libraries such as [Masonry](http://masonry.desandro.com/), this web component rearranges DOM elements instead of using CSS repositioning.
This allows better overall CSS support for styling elements, better support for flex/% based sizing, as well as retaining the ability to use nth-of-type CSS matchers.

## Automatic Element Ordering

### 3 Columns

![3 Columns](https://raw.githubusercontent.com/stevenrskelton/ordered-columns/master/examples/3columns.png "3 Columns")

### 2 Columns

![2 Columns](https://raw.githubusercontent.com/stevenrskelton/ordered-columns/master/examples/2columns.png "2 Columns")

## Documentation

> [About CSS Columns](http://stevenrskelton.github.io/ordered-columns/examples/about.html)

> [DOM Mutations](http://stevenrskelton.github.io/ordered-columns/examples/dom-mutation.html)

> [Template Repeat](http://stevenrskelton.github.io/ordered-columns/examples/template-repeat.html)

> [CSS Styles](http://stevenrskelton.github.io/ordered-columns/examples/css.html)

> [Auto Column Count](http://stevenrskelton.github.io/ordered-columns/examples/adaptive-number-of-columns.html)

## Live Examples

> [NASA Mission Timeline](http://stevenrskelton.github.io/ordered-columns/examples/nasa.html)

> [Halcyon Theme](http://stevenrskelton.github.io/ordered-columns/examples/halcyon.html)

## Usage

1. Add the library using the Javascript package manager [Bower](http://bower.io/):

	```bower install --save ordered-columns```

2. Import Web Components' polyfill:

	```html
	<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
	```

3. Import Custom Element:

	```html
	<link rel="import" href="bower_components/ordered-columns/ordered-columns.html">
	```

4. Start using it!

	Set the column count, and add content:

	```html
	<ordered-columns count="5">
		<!-- Any number of <article> or elements with role="article" -->
	</ordered-columns>
	```

## History

For detailed changelog, check [Releases](https://github.com/stevenrskelton/ordered-columns/releases).

## License
[MIT License](http://opensource.org/licenses/MIT) © Steven Skelton
