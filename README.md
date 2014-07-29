### Module System

The tools suite requires that `tools` itself be sourced, but everything else is optional. To load other modules, you use the helper method `tools__include` in your main bootstrap script to bring them in. Modules are responsible for resolving their own dependencies internally.

The argument to the function is simply a path from the `lib/` folder downwards to load into the scripting environment.

### Todo
