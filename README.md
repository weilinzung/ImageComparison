ImageComparison
[![npm](https://img.shields.io/npm/dt/image-comparison.svg)](https://www.npmjs.com/package/image-comparison)
[![npm](https://img.shields.io/npm/v/image-comparison.svg)](https://www.npmjs.com/package/image-comparison)
===============
Slider to quickly compare two images

## Install
```bash
$ npm install image-comparison --save
```

## Connection
### JavaScript
#### CommonJS
```js
import { ImageComparison } from 'image-comparison';
```
#### AMD
```js
require(['ImageComparison'], function (ImageComparison) {
   // Usage
});
```
### CSS
```html
<link rel="stylesheet" href="node_modules/image-comparison/src/ImageComparison.css">
```

## Usage
```html
<script>
new ImageComparison({ 
  container: containerSelector,
  startPosition: 70,
  data: [
    {
      image: images[0],
      label: 'before'
    },
    {
      image: images[1],
      label: 'after'
    }
  ],
});
</script>
```

## Options
Options list:
<table>
    <tr>
      <th>Name</td>
      <th>Description</th>
    </tr>
    <tr>
      <td>container</td>
      <td>Dom element for initialization ImageComparison</td>
    </tr>
   <tr>
      <td>startPosition</td>
      <td>starting position in percentage</td>
    </tr>
   <tr>
      <td>data</td>
      <td>Array of objects, where each object: `{ image: dom element, label: 'before'}`</td>
    </tr>
</table>


## Browsers support
Chrome, FF, Opera, Safari, IE10+

## Example
See example - <a href="https://m-ulyanov.github.io/image-comparison/">ImageComparison</a>
