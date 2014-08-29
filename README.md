# Project Base

A very simple, reliable module to solve the
`require('../../../../something.js')` problem.

## Usage

    var rootDir = require('project-base');
    var myModule = require(rootDir + 'lib/myModule.js');
