# Rewriting Array methods

Rebuilding javascript's array methods to both better understand them/their uses and get some practice with test-driven development.

Steps: 

- Read the docs, see what it's supposed to do. See what arguments it and the callback take
- Play with the native method, trying out weird edge cases
- Go into the debugger and see what the method is doing at each step
- List all of the test cases that immediately come to mind
- Think about edge cases, list those too
- Rewrite/simplify into multiple tests if necessary
- Build a prototype of how I -think- it should work
- Write a function signature (how it'll be used) and any callback params

Also: 

- Don't forget about edge cases! Empty arrays, holes, null, etc.
- See if the outputs from my method and the native one are the same, or at least as close as possible.