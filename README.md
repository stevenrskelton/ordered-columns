&lt;ordered-columns&gt;
================

Polymer Web Component that builds ordered columns (timeline) from arbitrary content.

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
		<!-- Any number of <section> or elements with role="section" -->
	</ordered-columns>
	```

## History

For detailed changelog, check [Releases](https://github.com/stevenrskelton/ordered-columns/releases).

## License
[MIT License](http://opensource.org/licenses/MIT) © Steven Skelton
