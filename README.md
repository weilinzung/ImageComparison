ImageComparison
===============
Slider to quickly compare two images



## Install
```bash
$ npm install image-comparison
```

## Usage
Once you have downloaded ImageComparison, the first thing you need to do is include the CSS and the JavaScript.

### CSS
```html
<link rel="stylesheet" href="path/ImageComparison.css">
```

### JavaScript
```html
<script src="path/ImageComparison.js"></script>
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

### commonJS
```js
  var ImageComparison = require('ImageComparison');
```

### ES6
```js
  import ImageComparison from 'ImageComparison';
```


##Options
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


##Browsers support
Chrome, FF, Opera, Safari, IE10+

##Example
See example - <a href="https://m-ulyanov.github.io/image-comparison/">ImageComparison</a>
