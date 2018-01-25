# v8-profiler-lambda

## Description

Wrapper library for [v8-profiler](https://github.com/node-inspector/v8-profiler)
with AWS Lambda compatible binaries.

This module forces the installation of the binaries necessary for running
v8-profiler on Lambda, in addition to the binaries matching the machine
running the node package manager.

*WARNING* - This module does _not_ provide a fully-integrated profiling experience for Lambda.
This is an advanced-use, low-level library for building profiling tools.  For the full 
experience, check out the 
[IOpipe AWS Lambda profiling plugin](https://github.com/iopipe/iopipe-plugin-profiler)

## Installation

### NPM

`npm install -s iopipe/v8-profiler-lambda`

### Yarn

`yarn add iopipe/v8-profiler-lambda`

## Usage

Require module:

`var v8profiler = require('v8-profiler-lambda')`

Refer to the documentation for [v8-profiler](https://github.com/node-inspector/v8-profiler).

## Authors

 - Pam Selle
 - Erica Windisch

## Copyright

2017 IOpipe
