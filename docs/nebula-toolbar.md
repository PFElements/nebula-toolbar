# \<nebula-toolbar\>

A toolbar control with support for accessibility.

The element manages selection behavior for a group of controls, ensuring that one, and only one control in the group is selected. If no initial control is selected, it will automatically select the first eligible control. Hidden and disabled controls can be included, but will be ignored from selection.

The element implements keyboard navigation behavior defined in the [WAI-ARIA](https://www.w3.org/TR/wai-aria-practices-1.1/#toolbar) authoring practices for **a11y**. The element uses a *roving index* strategy for navigation within the group, so any `tabindex` set on an individual control will be modified as necessary.

## Import

```html
<link rel="import" href="/bower_components/nebula-toolbar/nebula-toolbar.html"> 
```

## Usage

The following demonstrates the element with some common properties and events.

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

## Style

The element is styled using standard CSS properties.

```css
nebula-toolbar {
  background-color: black;
  color: white;
  height: 48px;
}
```

The element implements the `<nebula-select-behavior>` to support **a11y**. As the user navigates through through the toolbar with a keyboard or clicks any item it will be tagged with a `selected` property by default that can be used to style the active element if you are creating a menu.

```css
nebula-toolbar *[selected] {
  background-color: dimgrey;
}
```

## API Reference

### Mixins

#### [Nebula.SelectBehavior](https://www.webcomponents.org/element/arsnebula/nebula-select)

#### [Nebula.ElementMixin](https://www.webcomponents.org/element/arsnebula/nebula-element-mixin)