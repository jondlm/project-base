# Project Base **DEPRECATED**

There are situations where this module won't work. Since NPM now flattens your
dependency tree (usually a good thing) the assumption this module was built on
no longer holds true. I suggest [the wrapper] method instead, it's as easy as
requiring a module.

A very simple, module to solve the `require('../../../../something.js')`
problem. It relies on the fact that npm installs packages to `node_modules/`.

Don't use v1.0.1, it's broken.

## Usage

    var r = require('project-base');
    var myModule = require(r + 'lib/myModule.js');

[the wrapper]: https://gist.github.com/branneman/8048520#7-the-wrapper

