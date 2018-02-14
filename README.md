[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/mastercodekw/mcd-multi-select)

# \<mcd-multi-select\>

Web component that enables multi-selection from a given set of items.

## Usage

`<mcd-multi-select>` enables multi-selection from a given set of items. You can use the `selected-items` attribute to data-bind the items selected by the user, or simply use the `value` property to retrieve them.

```html
<mcd-multi-select items="{{items}}"></mcd-multi-select>
```

### Attributes

| Attribute | Description | Type | Default |
| --------- | ----------- | ---- | ------- |
| `opened` | Whether the dialog is opened or not | Boolean | false |
| `label` | The label to be shown to user | String | Label |
| `placeholder` | The placeholder to be shown to user in case he didn't select any item | String | - |
| `items` | Array containing selections to be shown to user | Array | - |
| `selected-items` | Array of selected items made by the user | Array | - |
| `prop` | Property shall be used for each item in case the user passed an array of objects | String | - |
| `filter-placeholder` | Placeholder for the filtering input field | String | Search... |
| `dismiss-title` | Title of the dismiss button | String | Dismiss |
| `toggle-title` | Title of the toggle-all button | String | Toggle All |
| `rtl` | Show layout for right-to-left languages | Boolean | false |

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --------------- | ----------- | ------- |
| `--mcd-multi-select-selection` | Mixin applied to each selection of the selected items | {} |
| `--mcd-multi-select-label ` | Mixin applied to label | {} |
| `--mcd-multi-select-placeholder` | Mixin applied to placeholder | {} |
| `--mcd-multi-select-dismiss` | Mixin applied to the dismiss button | {} |
| `--mcd-multi-select-dismiss-focus` | Mixin applied to the dismiss button when it is focused using the keyboard | {} |
| `--mcd-multi-select-dismiss-hover` | Mixin applied to the dismiss button when it is hovered | {} |
| `--mcd-multi-select-toggle` | Mixin applied to the toggle button | {} |
| `--mcd-multi-select-toggle-focus` | Mixin applied to the toggle button when it is focused using the keyboard | {} |
| `--mcd-multi-select-toggle-hover` | Mixin applied to the toggle button when it is hovered | {} |

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

Copyright (c) 2018  Mohammed ALSarraf <http://mastercodekw.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.