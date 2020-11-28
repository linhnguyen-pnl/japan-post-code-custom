# Japan Postal code
JavaScript module for Japan Postal Code.

Forked from https://github.com/linhnguyen-pnl/japan-post-code-custom.git

## How to install
```
npm install japan-postal-code-custom
```

## How to use

```js
import postal_code from 'japan-postal-code-custom';

let address = await postal_code.get(this.input);
console.log(address.prefecture); // => "東京都"
console.log(address.city); // => "千代田区"
console.log(address.area); // => "千代田"
console.log(address.street); // => ""
```

## LICENSE
MIT License
