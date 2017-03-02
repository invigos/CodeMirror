# CodeMirror
[![Build Status](https://travis-ci.org/codemirror/CodeMirror.svg)](https://travis-ci.org/codemirror/CodeMirror)
[![NPM version](https://img.shields.io/npm/v/codemirror.svg)](https://www.npmjs.org/package/codemirror)
[![Join the chat at https://gitter.im/codemirror/CodeMirror](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/codemirror/CodeMirror)  
[Funding status: ![maintainer happiness](https://marijnhaverbeke.nl/fund/status_s.png?again)](https://marijnhaverbeke.nl/fund/)

CodeMirror is a versatile text editor implemented in JavaScript for
the browser. It is specialized for editing code, and comes with over
100 language modes and various addons that implement more advanced
editing functionality.

A rich programming API and a CSS theming system are available for
customizing CodeMirror to fit your application, and extending it with
new functionality.

You can find more information (and the
[manual](http://codemirror.net/doc/manual.html)) on the [project
page](http://codemirror.net). For questions and discussion, use the
[discussion forum](https://discuss.codemirror.net/).

See
[CONTRIBUTING.md](https://github.com/codemirror/CodeMirror/blob/master/CONTRIBUTING.md)
for contributing guidelines.

The CodeMirror community aims to be welcoming to everybody. We use the
[Contributor Covenant
(1.1)](http://contributor-covenant.org/version/1/1/0/) as our code of
conduct.

### Quickstart

To build the project, make sure you have Node.js installed (at least version 6)
and then `npm install`. To run, just open `index.html` in your
browser (you don't need to run a webserver). Run the tests with `npm test`.

### Invigos

You need to install rollup globally first `npm i -g rollup`

Then setup other packages `npm i`

Set INVIGOS_PATH var to where you storing project
e.g. `INVIGOS_PATH='/home/alukin/proj/Invigos/E6Invigos'`
(on Linux it can be saved inside `~/.profile` so you don't need to re-type it each time)

after that you can use `npm run deploy` to build and deploy resulting codemirror lib into your webapp folder