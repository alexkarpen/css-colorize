## Appropriate credits first!
the code belongs to Barrett, my action was to wrap it into an npm package.
* [Barrett Sonntag](https://codepen.io/sosuke)
* [His codepen](https://codepen.io/sosuke/pen/Pjoqqp)

## Setup
To run this project, install it locally using npm:

```
$ npm install css-colorize
```


## Usage
```javascript
import colorize from 'css-colorize';
let css_filter = colorize.colorize('#f69240');

console.log(css_filter);
//expected output
/*{
  "values": [
    64.89040377148402,
    79.50872658754285,
    1413.6459379920873,
    92.2423101429785,
    102.91090347761539,
    92.90710884104686
  ],
  "loss": 0.30878495186012245,
  "filter": "filter: invert(65%) sepia(80%) saturate(1414%) hue-rotate(332deg) brightness(103%) contrast(93%);"
}*/
```

## Thank you for your attention!