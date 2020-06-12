# makeScript 
Make a callable script that creates a .bat file in script folder to act as a go between a folder in PATH and the script. Calling this on a file makes it callable and runnable from CMD.

```mkscript <TARGET> <NAME>```

TARGET: The path\name of your script compared to the current working directory. If a path is needed, or a file extension after name, NAME will be needed to name the script (command) being created.

NAME: Name of the created script and command.

The location the scripts are created in must be in the PATH varible.
