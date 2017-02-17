[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/arsnebula/nebula-toolbar)

[![Build Status](https://saucelabs.com/browser-matrix/arsnebula.svg)](https://saucelabs.com/beta/builds/e2cf012d864e408cb701c4ee6be3875e)

# \<nebula-toolbar\>

A web component to manage a group of toolbar controls.

* Simple container element to manage navigation for a group of controls
* Supports vertical and horizontal flexbox layout
* Supports [WAI-ARIA](https://www.w3.org/TR/wai-aria-practices-1.1/#toolbar) authoring practices for **a11y**

## Installation

```
$ bower install -S arsnebula/nebula-toolbar
```

## Usage

Import the element:

```html
<link rel="import" href="/bower_components/nebula-toolbar/nebula-toolbar.html"> 
```

Add and configure the element.

```html
<nebula-toolbar direction="vertical" selected="{{selected}}">
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