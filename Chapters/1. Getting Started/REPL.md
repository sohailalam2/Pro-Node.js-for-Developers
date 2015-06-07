# The Read-Eval-Print-Loop (REPL)

    Type node and press enter in terminal to enter REPL mode of Node.js
    Pressing CTRL+C twice from a blank line causes the REPL to terminate.
    
## REPL Commands

### .help
Displays all the available REPL commands.

### .exit
Terminates the REPL

### .break
Bail out of a multiline expression (without terminating the REPL)
For example:

```javascript
> for (var i = 0; i < 10; i++) {
... .break
>
```
    
### .save <filename>
Saves the current REPL session to the file specified in the filename

### .load <filename>
Executes the JavaScript file specified in the filename. The file is executed as if each line were typed directly into the REPL.

### .clear
Similar to .break, .clear can be used to terminate multiline expression. .clear is also used to reset the REPL's context object.
