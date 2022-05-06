# Ruby debugger on Replit

This is a demo for trying out Ruby's official debugger [ruby/debug](https://github.com/ruby/debug). 

Once you run the program, it should stop at a breakpoint in the `Foo#forth_call` method.

## Gain Context

- `bt` to see all the backtraces with rich information like call arguments
- `ls` to see what methods are available to the current `Foo` instance
- `info` to see variables accessible to the current scope and preview their values
- `<expr>` or `p <expr>` or `pp <expr>` to evaluate and print a Ruby expression


## Step Around

- `s[tep]` to step to the next breakable point
- `n[ext]` to step to the next line
- `c[ontinue]` to resume the program execution
- `up` to move up a frame
- `down` to move down a frame
- `f[rame] <num>` to move to a specific frame
  - You can use `bt` command to see all available frames




