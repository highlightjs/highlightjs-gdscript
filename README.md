# GDScript syntax for highlight.js

Syntax implementation of [Godot](https://godotengine.org/)'s GDScript language for [highlight.js](https://github.com/highlightjs/highlight.js).

### Authors

The original code was written by [Khairul Hidayat](https://github.com/khairul169). 
The repository was eventually maintained by 
- [Nelson Sylvest*r Fritsch](https://github.com/form-follows-function)
- [Calinou](https://github.com/Calinou)

### Documentation

 - https://highlightjs.org/
 - https://docs.godotengine.org/en/latest/getting_started/scripting/gdscript/gdscript_basics.html

### Building

To build a distribution version of this module you need to use tools provided by Highlight.js.

1. Checkout highlightjs/highlight.js from GitHub.
1. Create the `extra` folder in the root directory, if missing.
1. In the `extra` directory create a `gdscript` subdirectory and put the contents 
of this repository there.
1. Run build tools for the `cdn` target and you should see the `gdscript` language 
module being build alongside Highlight.js itself:

```
node ./tools/build.js -t cdn

...
Building extra\gdscript\dist/gdscript.min.js.
```
