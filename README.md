ImageComparison
===============
Slider to quickly compare two images


##Getting started
1. `npm install image-comparison --save`
2. Include style `node_modules/image-comparison/src/ImageComparison.css`
3. Call ImageComparison with your options:
```html
<script>
   import { ImageComparison } from './ImageComparison';

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
4. For support UMD use - `https://babeljs.io/docs/plugins/transform-es2015-modules-umd/`
5. Using!

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
