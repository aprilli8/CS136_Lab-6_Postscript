# Lab 6: P.S. It's Just a Stack

## Useful Links
 * [Course Homepage](https://williams-cs.github.io/cs136s19-www/) (with TA schedule)
 * [Lab Webpage](https://williams-cs.github.io/cs136s19-www/schedule.html)
 * [Token](https://williams-cs.github.io/cs136s19-www/assets/labs/lab6/javadoc/Token.html) documentation
 * [Reader](https://williams-cs.github.io/cs136s19-www/assets/labs/lab6/javadoc/Reader.html) documentation
 * [SymbolTable](https://williams-cs.github.io/cs136s19-www/assets/labs/lab6/javadoc/SymbolTable.html) documentation


## Repository Contents
This repository contains the starter files for writing and testing
your postscript interpreter.

 * In this lab, you should only need to modify `Interpreter.java`.
 * All files that end in `.ps` are postscript files. You should eventually be able to run them using your interpreter.

## Using Test files
There are several testing programs to help you verify your code as you go.
(You can always run your program interactively and type commands from the
command line as well.)

Rather than wait to test until you have implemented all of the commands,
create a smaller version of the test (the comment character in postscript is `%`),
and add new commands as you implement them.
Start with (a subset of) `basics.ps`!

```
$ java Interpreter < basics.ps
```
