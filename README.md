&lt;ordered-columns&gt;
================

Polymer Web Component that builds vertically ordered columns (timelines) from arbitrary DOM content.
Unlike CSS columns, earlier content is always rendered closer to the top of the page than later content.

Both the number of columns and column widths can be changed dynamically using Javascript or window resize events, ensuring elements are always rendered in the correct vertical order.

## Automatic Element Ordering

### 3 Columns

![3 Columns](https://raw.githubusercontent.com/stevenrskelton/ordered-columns/master/examples/3columns.png "3 Columns")

### 2 Columns

![2 Columns](https://raw.githubusercontent.com/stevenrskelton/ordered-columns/master/examples/2columns.png "2 Columns")

## Documentation

> [About CSS Columns](http://files.stevenskelton.ca/ordered-columns/examples/about.html)

> [DOM Mutations](http://files.stevenskelton.ca/ordered-columns/examples/dom-mutations.html)

> [Template Repeat](http://files.stevenskelton.ca/ordered-columns/examples/template-repeat.html)

> [CSS Styles](http://files.stevenskelton.ca/ordered-columns/examples/css.html)

## Live Examples

> [NASA Wikipedia with Images](http://files.stevenskelton.ca/ordered-columns/examples/nasa.html)

> [Halcyon Theme](http://files.stevenskelton.ca/ordered-columns/examples/halcyon.html)

## Usage

1. Add the library using the Javascript package manager [Bower](http://bower.io/):

	```bower install --save ordered-columns```

2. Import Web Components' polyfill:

	```html
	<script src="bower_components/platform/platform.js"></script>
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
