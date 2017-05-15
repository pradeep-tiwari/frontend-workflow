# frontend-workflow

Notes on frontend workflow and build process automation using Node.js, NPM, Bower, Grunt, and Yeoman.

#REPL: The Node Shell

Stands for "Read-Eval-Print-Loop". 

- Simply run `$ node` to launch the REPL prompt.
- Run `$ .help` for available commands.
- Expressions with `var` keyword are stored but not returned.
- Previously returned value can be accessed via a special `_` (underscore) variable.
- Inspect a Node module via `require` command.
- Create you own REPLs via `repl` module.

```
$ node
> 1 + 1
> 2
> _ + 2
> 4
```
```
$ node
> x = 2
> 2
> var y = 3
> undefined
> y
> 3
```
```
$ node
> util = require('util')
```
