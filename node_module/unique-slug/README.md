unique-slug
===========

Generate a unique character string suitible for use in files and URLs.

```
var uniqueSlug = require('unique-slug')

var randomSlug = uniqueSlug()
var fileSlug = uniqueSlug('/etc/passwd')
```

### uniqueSlug(*str*) → String (8 chars)

If *str* is passed in then the return value will be its murmur hash in
hex.

If *str* is not passed in, it will be 4 randomly generated bytes
converted into 8 hexadecimal characters.