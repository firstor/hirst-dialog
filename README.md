# hirst-dialog

`hirst-dialog` is a Polymer-based web component to implement web dialogs.

## How to use

To install the element:
```
$ bower install hirst-dialog
```

### hirst-action-dialog
```html
<hirst-action-dialog
    id="dialog"
    title="Congratulations">
    It works!
</hirst-action-dialog>
```

### hirst-confirm-dialog
```html
<hirst-confirm-dialog
    id="dialog"
    title="Congratulations"
    confirm-title="CONFIRM"
    dismiss-title="DISMISS">
    It works!
</hirst-confirm-dialog>
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
http://localhost:3030/components/hirst-dialog/
```

### Running Tests

```
$ polymer test
```

