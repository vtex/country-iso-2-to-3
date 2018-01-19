# country-iso-2-to-3

> Convert a country code ISO 3166-1 Alpha-2 to ISO 3166-1 Alpha-3

## Install

```sh
$ npm install country-iso-2-to-3
```

## Usage

```js
const getCountryISO3 = require("country-iso-2-to-3");

getCountryISO3("BR")
// "BRA"

getCountryISO3("US")
// "USA"
``` 

## API

### getCountryISO3(countryCode)

**Parameter**:
A string with a country code in ISO 3166-1 Alpha-2

**Return**:
A string with the country code in ISO 3166-1 Alpha-3

---

## License

MIT © [VTEX](https://www.vtex.com)
