# File Cookie Store

tough-cookie-filestore is a JSON file-based CookieStore for the [tough-cookie module](http://npmjs.com/package/tough-cookie). See 
[tough-cookie documentation](https://github.com/goinstant/tough-cookie#constructionstore--new-memorycookiestore-rejectpublicsuffixes) for more info.


## Installation

    $ npm install tough-cookie-filestore

## Options

  `path` file path of cookiejar.

## Usage
```js
  var FileCookieStore = require("tough-cookie-filestore");
  var CookieJar = require("tough-cookie").CookieJar;

  var jar = new CookieJar(new FileCookieStore("./cookie.json"));
```
## License

 MIT
