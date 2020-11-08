# learn_pseudocode

## Begin

Execute pseudocode by typing

`pseudo execute NAME`

where

`NAME`

is a file called NAME.pseudo

You can also have combine multiple files into one execution:

`pseudo execute NAME1 NAME2`

## Errors

You do get tracebacks when there is an issue. It will output both the original pseudocode and the converted Python.

It also provides line number. However, note that if you are executing multiple files, the line number will report the line number at the combined file.

## Additional commands

- `pseudo transpile NAME1` to view how your pseudocode is translated ("transpiled") into python
- `pseduo run` to run all .pseudo files