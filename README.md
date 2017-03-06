[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/arsnebula/nebula-toolbar)
[![Gitter chat](https://badges.gitter.im/org.png)](https://gitter.im/arsnebula/webcomponents)

[![Build Status](https://saucelabs.com/browser-matrix/arsnebula.svg)](https://saucelabs.com/beta/builds/8a8a83bd1126477ca71e2f4291b74eaf)

# \<nebula-toolbar\>

A web component to manage keyboard accessibility for a set of toolbar controls.

* Simple toolbar or menu container element
* Flexbox layout automatically centers and spaces toolbar children
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
<nebula-toolbar>
  <nebula-icon-button icon="editor:format-bold"></nebula-icon-button>
  <nebula-icon-button icon="editor:format-italic"></nebula-icon-button>
  <nebula-icon-button icon="editor:format-list-numbered"></nebula-icon-button>
  <nebula-icon-button icon="editor:format-list-bulleted"></nebula-icon-button>
  <nebula-icon-button icon="editor:format-align-left"></nebula-icon-button>
  <nebula-icon-button icon="editor:format-align-right"></nebula-icon-button>
  <nebula-icon-button icon="editor:attach-file"></nebula-icon-button>
</nebula-toolbar>
```

Style the element.

```css
nebula-toolbar {
  background-color: black;
  color: white;
  height: 48px;
}
nebula-toolbar *[selected] {
  background-color: dimgrey;
}
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