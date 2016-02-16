# Debugging in Node
Set `debugger` in your code to set a breakpoint. Then run your file with `node debug ${filename}`

## commands:
* cont, c - continue execution
* next, n - step next
* step, s - step in
* out, o - step out

when you hit a breakpoint, call `repl`. You can then access all the variables within the current closure.

advanced usage: 'node debug -p <pid>' - connects to process via pid
