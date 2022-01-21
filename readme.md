
# Breadth.JS

Where to find JavaScript utilities you might need. Often times I have found myself having to search stackoverflow for an obscure utility, or just default to writing my own because finding one on NPM that works properly would be energy consuming. So this list hopes to list out as many utilities as possible and where you can find them, to speed up coding your project!

As an additional note, these are basically the libraries you should learn to give you an edge in terms of speed when getting things done. They are typically long-standing and "stable" APIs, and learning them will be a skill you could transfer to any JavaScript or Node.js project.

## Utility Collections

Try some of these to see if they include what you need. If not, then try below. If we are missing something for which you find a solution, please send us a PR!

- lodash
- underscore
- [stdlib-js](https://github.com/stdlib-js/stdlib)
- [mout](https://github.com/mout/mout)

## Assorted One-off Utilities by Type

### String

- chunk a string into equal sized chunks
- convert between string cases
  - [to-case](https://github.com/ianstormtaylor/to-case)
- string diff
  - [diff-match-patch](https://github.com/google/diff-match-patch/wiki/Language:-JavaScript)
  - [fast-diff](https://github.com/jhchen/fast-diff)
  - [jsdiff](https://github.com/kpdecker/jsdiff)
- utf conversions
  - [string-utf16-to-utf8-array](https://github.com/stdlib-js/string-utf16-to-utf8-array)

### Array

- chunk an array into equal sized chunks
  - [chunk-array](https://github.com/haio/chunk-array)
- shuffle array

### Number

- random number between min and max
- probable prime test
- exact prime test
- https://github.com/soatok/constant-time-js

### BigInt

[Some notes](https://github.com/juanelas/bigint-crypto-utils/blob/master/docs/API.md).

- generic BigInt functionality
  - [js-big-integer](https://github.com/Yaffle/BigInteger)
- random bigint between min and max
  - [js-random-bigint](https://github.com/japan-d2/js-random-bigint)
- cryptographically secure bigints
  - [bigint-secrets](https://github.com/juanelas/bigint-secrets)

### Date

- manipulate dates
  - [luxon](https://github.com/moment/luxon)
  - [moment](https://github.com/moment/moment)
  - [date-fns](https://github.com/date-fns/date-fns)

### Binary

- https://github.com/lancejpollard/bit.js

### Hashing

- https://github.com/mixu/perfect
- https://github.com/paulmillr/noble-hashes
- https://github.com/3rd-Eden/node-hashring
- https://github.com/dashpay/x11-hash-js
- https://github.com/search?l=JavaScript&p=2&q=hash-algorithm&type=Repositories
- https://github.com/MatthewBarker/hash-string/blob/master/source/hash-string.js
- https://github.com/kornelski/bcrypt/blob/master/bCrypt.js
- https://github.com/bigeasy/hash
- https://github.com/codefrom/cryptonight-js/blob/master/lib/skein.js

Some [specification papers](https://en.wikipedia.org/wiki/Comparison_of_cryptographic_hash_functions). [SHA3](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.202.pdf), [BLAKE3](https://github.com/BLAKE3-team/BLAKE3-specs/blob/master/blake3.pdf)

### Crypto

- https://github.com/indutny/elliptic

### CSV

- parsing csvs
  - [csv-parse](https://github.com/adaltas/node-csv/tree/master/packages/csv-parse/)
- stringify array of records to csv
  - [csv-stringify](https://github.com/adaltas/node-csv/tree/master/packages/csv-stringify)

### XLSX (Spreadsheets)

- working with spreadsheets
  - [sheetjs](https://github.com/sheetjs/sheetjs)

### ARIA

- https://github.com/w3c/aria-practices
- https://github.com/w3c/aria

## Hash Table

- https://github.com/xa1d3n/JavaScript-DataStructures

### JSON

- diff and patch json objects
  - [jsondiffpatch](https://github.com/benjamine/jsondiffpatch)
- streaming parse large json files
  - [stream-json](https://github.com/uhop/stream-json)
- array diffing
  - [fast-array-diff](https://github.com/YuJianrong/fast-array-diff)

### XML

- streaming parse large XML files
  - [sax-js](https://github.com/isaacs/sax-js)
- https://github.com/nashwaan/xml-js

### YAML

- basic yaml functions
  - [js-yaml](https://github.com/nodeca/js-yaml)

### FormData

- streaming form data parser
  - [busboy](https://github.com/mscdex/busboy)

### Cookies

### CSRF

### CORS

### ANSI

### Terminal

- terminal text/string styling
  - [chalk](https://github.com/chalk/chalk)
- terminal ui
  - [blessed](https://github.com/chjj/blessed)
- https://github.com/termstandard/colors

### File

- stdlib for file handling
  - [fs](https://nodejs.org/api/fs.html)

### i18n

### Color

- [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript.
- [PleaseJS](https://github.com/Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes.

### Security

- oauth2
  - [oauth2-server](https://github.com/oauthjs/node-oauth2-server)
- tls
  - [forge](https://github.com/digitalbazaar/forge)

### Web Storage

First, [some notes](https://github.com/softvar/awesome-web-storage).

### DOM

- webpage rendering
  - [puppeteer](https://github.com/puppeteer/puppeteer)

### PDF

### Font

### Geo

- geohash
  - [ngeohash](https://github.com/sunng87/node-geohash)
- geospatial indexing
  - [h3.js](https://github.com/uber/h3-js)

### HTTP

- fetch API
  - [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch)

### WebAudio

### WebAssembly

### PRNG

- quadratic residue prng (not secure)
  - [configured-quadratic-residue-prng.js](https://github.com/lancejpollard/configured-quadratic-residue-prng.js)

### 3rd Party APIs

- [aws-sdk]()
