&lt;sorted-columns&gt;
================

Polymer Web Component that builds ordered columns (timeline) from arbitrary content.

## Live Examples and Documentation

> [Articles](http://files.stevenskelton.ca/sorted-columns/examples/eff.html)

## Usage

1. Add the library using the Javascript package manager [Bower](http://bower.io/):

	```bower install --save sorted-columns```

2. Import Web Components' polyfill:

	```html
	<script src="bower_components/platform/platform.js"></script>
	```

3. Import Custom Element:

	```html
	<link rel="import" href="bower_components/sorted-columns/sorted-columns.html">
	```

4. Start using it!

	Set the column count, and add content:

	```html
	<sorted-columns count="5">
		<!-- Any number of <section> or elements with role="section" -->
	</sorted-columns>
	```

## History

For detailed changelog, check [Releases](https://github.com/stevenrskelton/sorted-columns/releases).

## License
[MIT License](http://opensource.org/licenses/MIT) © Steven Skelton
