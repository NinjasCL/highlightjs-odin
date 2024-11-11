# Odin plugin for Highlight.js

This grammar was [Extracted from Odin Website](https://github.com/odin-lang/odin-lang.org/blob/master/themes/odin/layouts/partials/head.html#L71)

Odin is a general-purpose programming language with distinct typing built
for high performance, modern systems and data-oriented programming.

Odin is the C alternative for the Joy of Programming.

```odin
package main 

import "core:fmt"

main :: proc() {
	fmt.println("Hellope!")
}
```

Code minified with: https://www.toptal.com/developers/javascript-minifier

## Installing Odin

- Getting Started - https://odin-lang.org/docs/install/ Instructions for downloading and install the Odin compiler and libraries.

## Learning Odin

- Getting Started - https://odin-lang.org/docs/install/
- Getting Started with Odin. Downloading, installing, and getting your irst program to compile and run.
- Overview of Odin - https://odin-lang.org/docs/overview/ An overview of the Odin programming language and its features.
- Frequently Asked Questions (FAQ) - https://odin-lang.org/docs/faq/ Answers to common questions about Odin. 

- Packages - https://pkg.odin-lang.org/ Documentation for all the official packages part of the core and vendor library collections.
- Nightly Builds - https://odin-lang.org/docs/nightly/ Get the latest nightly builds of Odin.
- More Odin Examples - https://github.com/odin-lang/examples This repository contains examples of how certain things can be accomplished in idiomatic Odin, allowing you learn its semantics, as well as how to use  parts of the core and vendor package collections.

## Description

odin - a language grammar for highlightjs

### Static website or simple usage

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" charset="UTF-8"
  src="/path/to/highlightjs-odin/dist/odin.min.js"></script>
<script type="text/javascript">
  hljs.highlightAll();
</script>
```

### Using directly from the UNPKG CDN

```html
<script type="text/javascript"
  src="https://unpkg.com/highlightjs-odin@1.0.1/dist/odin.min.js"></script>
```

- More info: <https://unpkg.com>

### With Node or another build system

If you're using Node / Webpack / Rollup / Browserify, etc, simply require the language module, then register it with Highlight.js.

```javascript
var hljs = require('highlightjs');
var hljsodin = require('highlightjs-odin');

hljs.registerLanguage("odin", hljsodin);
hljs.highlightAll();
```
