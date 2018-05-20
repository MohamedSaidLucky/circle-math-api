# circle-math-api

this is a demo package for calculating circle math

### version
  @1.0.6

### install
```
npm i circle-math-api --save
```

### Usage

```javascript

const Circle = require('circle-math-api');

var radius = 5;

var area = Circle.area(radius);
var perimeter = Circle.perimeter(radius);

console.log(`Area is ${area} . `);
console.log(`Perimeter is ${perimeter} . `);

```
