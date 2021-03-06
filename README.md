# image-gallery

A Polymer Element showing a gallery of image thumbnails that each open an image-gallery-popup when clicked or tapped.

### Example

```js
var images = [{
  id: 1,
  link: 'https://github.com/DigElements',
  name: 'DIG',
  source: 'dig.png'
}, {
  id: 2,
  link: 'https://nextcentury.com',
  name: 'Next Century',
  source: 'NextCentury.png'
}];
```

```html
<image-gallery images="[[images]]"></image-gallery>
```

### Styling

`<image-gallery>` provides the following custom properties and mixins for styling:

Custom property                  | Description                                  | Default
---------------------------------|----------------------------------------------|--------
`--image-gallery-hovering-color` | The background color of the hovering images. | --paper-grey-300
`--image-gallery-selected-color` | The background color of the selected images. | --paper-grey-300
`--image-gallery-label-style`    | The style of the label.                      | none

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

