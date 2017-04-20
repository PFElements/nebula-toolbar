[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-green.svg)](https://www.webcomponents.org/element/arsnebula/nebula-icon-button)
[![Polymer Version](https://img.shields.io/badge/polymer-v2-blue.svg)](https://www.polymer-project.org)
[![Sauce Labs Build Status](https://img.shields.io/badge/saucelabs-passing-red.svg)](https://saucelabs.com/beta/builds/897ce1297bb44e36a70030769f0d9bfc)
[![Gitter Chat](https://badges.gitter.im/org.png)](https://gitter.im/arsnebula/webcomponents)
[![Become a Patreon](https://img.shields.io/badge/patreon-support_us-orange.svg)](https://www.patreon.com/arsnebula)

# \<nebula-toolbar\>

A toolbar control with support for accessibility.

* Simple toolbar or menu container element
* Flexbox layout automatically centers and spaces toolbar children
* Supports [WAI-ARIA](https://www.w3.org/TR/wai-aria-practices-1.1/#toolbar) authoring practices for **a11y**

## Installation

```sh
$ bower install -S arsnebula/nebula-toolbar
```

## Getting Started

Import the element.

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

*For more information, see the API documentation.*

## Contributing

We welcome and appreciate feedback from the community. Here are a few ways that you can show your appreciation for this package:

* Give us a **Star on GitHub** from either [webcomponents.org](https://www.webcomponents.org/element/arsnebula/nebula-element-mixin) or directly on [GitHub](https://github.com/arsnebula/nebula-element-mixin).

* Submit a feature request, or a defect report on the [Issues List](https://www.webcomponents.org/element/arsnebula/nebula-element-mixin/issues).

* Become a [Patreon](https://www.patreon.com/arsnebula). It takes a lot of time and effort to develop, document, test and support the elements in our [Nebula Essentials](https://www.webcomponents.org/collection/arsnebula/nebula-essentials) collection. Your financial contribution will help ensure that our entire collection continues to grow and improve.

If you are a developer, and are interested in making a code contribution, consider opening an issue first to describe the change, and discuss with the core repository maintainers. Once you are ready, prepare a pull request:

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Change Log

See [CHANGELOG](/CHANGELOG.md)

## License

See [LICENSE](/LICENSE.md)