# codename-nordic

> Nordic deities names parser for [Codename](https://github.com/khaosdoctor/Codename) (Standalone)

## Usage

Install the package using either `npm install codename-nordic --save` or `yarn add codename-nordic`.

Require it and use the function `parse`:

```js
const nordic = require('codename-nordic')

console.log(nordic.parse('2.1.4').codenameText) // V2.1.4 - Borr
```

For more information about the API, see [Codename](https://github.com/khaosdoctor/Codename) project, this parser only abstracts the `parse` function, returning an instance of the original Codename parser