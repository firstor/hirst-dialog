# komed-dialog

`komed-dialog` is a Polymer-based web component to implement various dialogs for Komed-Health.

## How to use

To install the element:
```
$ bower install komed-dialog
```

### komed-action-dialog
```html
<komed-action-dialog
    id="dialog"
    title="Congratulations">
    It works!
</komed-action-dialog>
```

### komed-confirm-dialog
```html
<komed-confirm-dialog
    id="dialog"
    title="Congratulations"
    confirm-title="CONFIRM"
    dismiss-title="DISMISS"
    show-dismiss>
    It works!
</komed-confirm-dialog>
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
http://localhost:3030/components/komed-dialog/
```

### Running Tests

```
$ polymer test
```

