component-compile
=================

Component sub-command to pre-compile all your .ejs files to requirable js files

## Installation

  With [Component](http://github.com/component/component) previously installed:

  npm install -g
  
## Pre-compile all your ejs files

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
