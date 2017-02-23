# ardenshell
## pythony shell-like for quick interactive hacks

-----

### Goal:

Quick and dirty interactive shell for capturing user input
and doing meaningful things with it easily. This is a practice in 
dogfooding. 

### Currently:

- Binds keywords and arguments to arbitrary function calls
- Binds function calls to loop with addLoopMethod. Defined methods are called once per input loop -- this is how we'll achieve state.
- Basic (optional) I/O loop with raw_input(). Can be turned off with ArdenShell.loop(noIO=True) if you're handling I/O elsewhere.
- Customizable banner and others. 


### Next Steps:
- Return values from addLoopMethod()s 
- addPreLoopMethod() -- fire some setup scripts before you jump into the loop
- Better State
- Docs. 
