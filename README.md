ImageComparison
===============
Slider to quickly compare two images


## Install
```bash
$ npm install image-comparison
```

## Connection
### JavaScript
#### commonJS
```js
var ImageComparison = require('ImageComparison');
```
#### ES6
```js
import ImageComparison from 'ImageComparison';
```
#### Simple Path
```html
<script src="yourpath/ImageComparison.js"></script>
```

### CSS
```html
<link rel="stylesheet" href="yourpath/ImageComparison.css">
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
