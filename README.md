## Example 
```code
const nayan = require('imran-alldl-media');

nayan.alldown('url')
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error('Error downloading:', error);
  });
```
