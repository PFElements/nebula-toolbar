[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/arsnebula/nebula-toolbar)
[![Gitter chat](https://badges.gitter.im/org.png)](https://gitter.im/arsnebula/webcomponents)

[![Build Status](https://saucelabs.com/browser-matrix/arsnebula.svg)](https://saucelabs.com/beta/builds/cc0a235e6d724ec49d8cc49a3ed08be7)

# \<nebula-toolbar\>

A web component to manage keyboard accessibility for a set of toolbar controls.

* Simple container element to manage navigation and selection for a group of controls
* Supports vertical and horizontal flexbox layout
* Supports [WAI-ARIA](https://www.w3.org/TR/wai-aria-practices-1.1/#toolbar) authoring practices for **a11y**

## Installation

```sh
$ bower install -S arsnebula/nebula-toolbar
```

## Usage

Import the element:

```html
<link rel="import" href="/bower_components/nebula-toolbar/nebula-toolbar.html"> 
```

Add and configure the element.

```html
<nebula-toolbar direction="vertical" selected="{{selected}}" on-selected="_onSelected">
  <a>Link1</a>
  <a>Link2</a>
  <a>Link3</a>
</nebula-toolbar>
```

*For more information on element properties and methods see the element API documentation.*

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Change Log

See [CHANGELOG](/CHANGELOG.md)

## License

See [LICENSE](/LICENSE.md)