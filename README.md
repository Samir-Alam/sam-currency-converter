# sam-currency-converter

An npm package to convert currencies

<hr>

# Getting Started

## 🐇 Installation

Install sam-currency-converter with via your package manager:

```bash
npm install sam-currency-converter
```

Then import the convertCurrency component:

```js
import {convertCurrency} from 'sam-currency-converter'

const fromCurrency = 'USD'; // From which currency to convert
const toCurrency = 'INR';   // To which currency to convert
const numberOfUnits = 5;    // Number of units to be converted

convertCurrency(fromCurrency, toCurrency, numberOfUnits).then(res=>console.log(res));
```

## 🧑‍🎓 License

sam-currency-converter is Apache licensed.
