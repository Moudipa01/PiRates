# PiRates
Beautiful math in all browsers


by [Moudipa Jana](https://github.com/Moudipa01)

Pirates is a web formula editor designed to make typing math easy and beautiful.

<img alt="homepage demo" src="https://cloud.githubusercontent.com/assets/225809/15163580/1bc048c4-16be-11e6-98a6-de467d00cff1.gif" width="260">

This is committed to getting things running smoothly for calculating maths. 

## Getting Started

Pirates has a simple interface. This brief example creates a pirates element and renders, then reads a given input:
```javascript
var htmlElement = document.getElementById('some_id');
var config = {
  handlers: { edit: function(){ ... } },
  restrictMismatchedBrackets: true
};
var mathField = MQ.MathField(htmlElement, config);

mathField.latex('2^{\\frac{3}{2}}');
mathField.latex(); // => '2^{\\frac{3}{2}}'
```

Check out the project [Getting Started Guide](https://github.com/Moudipa01/PiRates) for setup instructions and basic pirates usage.

## Contact the Developer:

Email- moudipa.jana2020@vitstudent.ac.in
