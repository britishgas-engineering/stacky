[![NPM version](http://img.shields.io/npm/v/stacky.svg)](https://npmjs.org/package/stacky)
[![Build Status](http://img.shields.io/travis/PolymerLabs/stacky.svg)](https://travis-ci.org/PolymerLabs/stacky)

# Health Warning

Stacky repo is Read Only 1.3.1 • Public • Published 4 years ago.

This is a fork for security patches only. If the original repo springs back to life please use that instead.

# Stacky

## Formatting

`stacky.pretty(error.stack)`:

![Example Pretty Stack](example.png?raw=true)

`pretty` Provides [several options](lib/formatting.js#L15-L36) allowing you to
tweak the output format to your liking.


## Parsing

`stacky.parse(error.stack)`:

```js
[
  {
    method:   'thingCalled',
    location: 'some/file.js',
    line:     1,
    column:   2,
  }
  ...
]
```
