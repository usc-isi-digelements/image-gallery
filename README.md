# image-gallery

A Polymer Element showing a gallery of image thumbnails that each open an image-gallery-popup when clicked or tapped.

### Example
```html
<image-gallery images="[[array]]"></image-gallery>
```

### Styling

`<image-gallery>` provides the following custom properties and mixins for styling:

Custom property          | Description                                  | Default
-------------------------|----------------------------------------------|--------
`--image-hovering-color` | The background color of the hovering images. | none
`--image-selected-color` | The background color of the selected images. | none

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

