# require-doge

>  directly require [dogescript](https://github.com/dogescript/dogescript) files in node

[![Build Status](https://secure.travis-ci.org/dogescript/require-doge.svg?branch=master)](http://travis-ci.org/dogescript/require-doge) [![Dependency Status](https://david-dm.org/dogescript/require-doge.svg)](https://david-dm.org/dogescript/require-doge) [![NPM version](https://badge.fury.io/js/require-doge.svg)](http://badge.fury.io/js/require-doge)

![wow](https://raw.github.com/dogescript/require-doge/master/media/doge-01.jpg)

     require dogescript
          such node
        wow

# Todo

- add DSON support

## Install

````
npm install require-doge --save
````

## Usage

````js
require('require-doge');

var amaze = require('./doge.djs');
````

Check loaded extension:

```bash
$ node
> require('./index.js')
> require.extensions
{ '.js': [Function],
  '.json': [Function],
  '.node': [Function],
  '.djs': [Function: compile] }
```

## History

* 0.1.6 - moved to dogescript org
* 0.1.4 - node no beauty
* 0.1.3 - fix doge
* 0.1.0 - top doge


## Contributing

In lieu of a formal styleguide, take care to maintain the existing doge style.


## License

Copyright (c) 2014 [Bart van der Schoor](https://github.com/Bartvds)

Licensed under the MIT license.
