# Minishell

This project is about creating a simple SHELL: our little Bash. 
It's a group project and there were two of us in it.

## Overview

Our shell should:
* Display a prompt when waiting for a new command.
* Have a working history.
* Search and launch the right executable (based on the PATH variable or using a
relative or an absolute path).
* Use one global variable to indicate a received signal.
* Handle ’ (single quote) which should prevent the shell from interpreting the meta-
characters in the quoted sequence.
* Handle " (double quote) which should prevent the shell from interpreting the meta-
characters in the quoted sequence except for $ (dollar sign).
* Handle the following redirections: < (redirect input), << (heredoc), >> (redirect output in append mode), > (redirect output)
* Handle pipe
* Handle environment variables ($ followed by a sequence of characters) which
should expand to their values.
* Handle $? which should expand to the exit status of the most recently executed
foreground pipeline.
* Handle ctrl-C, ctrl-D and ctrl-\ which should behave like in bash.
* In interactive mode:
* ctrl-C displays a new prompt on a new line.
* ctrl-D exits the shell.
* ctrl-\ does nothing.

it doesn't interpret unclosed quotes or special characters which are not required by the
subject such as \ (backslash) or ; (semicolon).


• Our shell implement the following built-in commands:
* echo with option -n
* cd with only a relative or absolute path
* pwd with no options
* export with no options
* unset with no options
* env with no options or arguments
* exit with no options


## Installing and Compiling Minishell

Clone the repository

```shell
https://github.com/guillaumeschwartz76/Minishell.git
```

You can go to the directory for compilation and can do ```make```.

## Executing Minishell

```shell
./minishell
```

You have now access to our prompt and you can test minishell.

Have Fun