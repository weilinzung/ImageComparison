ImageComparison
===============
Slider to quickly compare two images


##Getting started
1. `npm install image-comparison` or download ZIP arhive
2. Include ImageComparison.js and ImageComparison.css<br>
2.1 IE9 required file classList.js
3. Call ImageComparison with your options:
```html
<script>
   new ImageComparison({
      container: container element,
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
      <td>Array of objects, where each object: { image: dom element, label: 'before'}</td>
    </tr>
</table>


##Browsers support
Chrome, FF, Opera, Safari, IE9+

##Example
See example - <a href="https://m-ulyanov.github.io/image-comparison/">ImageComparison</a>
