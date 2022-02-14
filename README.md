# UnwantedSdk
🔮 Studio Unwanted's Software Developement Kit for the web ⚒️

## Installing 
- Add the SDK to your project by running `yarn add @studiounwanted/sdk` or `npm install @studiounwanted/sdk`

## Usage

- Convert large integer valeus represented as exponentials, strings, or big numbers into human readable large numbers

```js
Import { Methods as UnwantedMethods } from '@studiounwanted/sdk'


const exponent = 8.21e16

UnwantedMethods.parseStringifiedNumber(exponent) // 82100000000000000
```

- Convert large numbers into prefixed S.I Numbers. Ex 1000000 = 1M

```js
Import { Methods as UnwantedMethods } from '@studiounwanted/sdk'


const bigMoney = 8.21e9

UnwantedMethods.toSI(bigMoney) // 8.21B
```

