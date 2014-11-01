&lt;ordered-columns&gt;
================

Polymer Web Component that builds ordered columns (timeline) from arbitrary content.
Unlike CSS columns, content is always ordered so that earlier content is closer to the top of the page than later content.

## Automatic Element Ordering

### 3 Columns

![3 Columns](https://raw.githubusercontent.com/stevenrskelton/ordered-columns/master/examples/3columns.png "3 Columns")

### 2 Columns

![2 Columns](https://raw.githubusercontent.com/stevenrskelton/ordered-columns/master/examples/3columns.png "2 Columns")

## Live Examples and Documentation

> [Articles](http://files.stevenskelton.ca/ordered-columns/examples/eff.html)

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
