# Chap 1 - Exercise 3

## Question

Experiment with modifying the formatting in the “Hello, world!” program. Add blank lines, spaces, change indentation,
insert newlines.

1. After making a modification, run `go fmt` to see if the formatting change is undone.
2. Also, run `go build` to see if the code still compiles.
3. You can also add additional fmt.Println calls so you can see what happens if you put blank lines in the middle of a
   function.

## Answer

1. `go fmt` will format the changes:

    - Remove any extra spaces.
    - Change the indentation to tab (with correct indent level)

2. `go build` will compiles the code just as before (with or without formatting)

3. For multi blank lines, `go fmt` will trim them to 1 blank line. 