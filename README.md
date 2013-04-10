component-compile
=================

Component sub-command to pre-compile all your .ejs files to requirable js files.  Sorry does not work on Windows :(

## Installation

  With [Component](http://github.com/component/component) previously installed:
```
  $ npm install -g component-compile
```

## Pre-compile all your ejs files recursively

```
  $ component compile <dir>
```

## Render your html

```
  //template.ejs has previously been compiled to template.js
  var Template = require('./template');
  var html = Template({
    title:'Pre-compiling is cool'
  });

```
