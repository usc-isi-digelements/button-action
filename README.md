# button-action

A Polymer Element showing a stylized button that executes an action when clicked or tapped.

### Example
```html
<button-action
  text="Click Me"
  click-listener="[[listener]]">
</button-action>
```

### Styling

`<button-action>` provides the following custom properties and mixins for styling:

Custom property                    | Description                         | Default
-----------------------------------|-------------------------------------|--------
`--button-action-background-color` | The background color of the button. | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

