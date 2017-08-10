# komed-dialog-base

`komed-dialog-base` is a Polymer-based web component to implement a dialog base for Komed-Health.

## How to use

To install the element:
```
$ bower install komed-dialog-base
```

```html
<komed-dialog-base
    id="dialog"
    title="Congratulations">
    It works!
</komed-dialog-base>
```

## Development

### Prerequisites

[Polymer CLI](https://www.npmjs.com/package/polymer-cli) and [Bower](https://www.npmjs.com/package/bower) should be installed globally.
```
$ npm install polymer-cli --global
$ npm install bower --global
```

Then install all components required in the project:
```
$ bower install
```

### Viewing element

To view reusable component on the browser:
```
$ polymer serve
```

Then open the browser and go to the url the terminal or console implies, something like this:
```
http://localhost:3030/components/komed-dialog-base/
```

### Running Tests

```
$ polymer test
```

