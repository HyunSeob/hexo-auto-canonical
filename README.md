# hexo-auto-canonical
[![Downloads](https://img.shields.io/npm/dm/hexo-auto-canonical.svg)](https://www.npmjs.com/package/hexo-auto-canonical) [![npm](https://img.shields.io/npm/v/hexo-auto-canonical.svg)](https://www.npmjs.com/package/hexo-auto-canonical) [![LICENSE](https://img.shields.io/npm/l/hexo-auto-canonical.svg)](LICENSE)

A generator automatically make canonical link for hexo.
You could use this module for your SEO of blog powered by hexo.

## Installation
```
npm install --save hexo-auto-canonical
```

## Usage
Add an auto canonical helper simply to your html's `<head>` block as follows:

with ejs,
``` ejs
<%- autoCanonical(config, page) %>
```
OR with jade,
``` jade
| !{ autoCanonical(config, page) }
```

## License
Copyright (c) 2016, HyunSeob. Licensed under the [MIT license](https://github.com/HyunSeob/hexo-auto-canonical/blob/master/LICENSE).

