# Project Base

A very simple, reliable module to solve the
`require('../../../../something.js')` problem. It relies on the fact that npm
installs packages to `node_modules/`.

Don't use v1.0.1, it's broken.

## Usage

    var r = require('project-base');
    var myModule = require(r + 'lib/myModule.js');
