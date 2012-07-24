hello-cl
========

Basic Common Lisp project to learn Lisp syntax and lack thereof.

## Resources

Don't get intimidated. :)

Check out the first few chapters in the following books:

- ANSI Common Lisp
- On Lisp (chapter 2, for instance)
- Paradigms of Artificial Intelligence Programming: Case Studies in Common Lisp

They have introductions to Lispy concepts. Fortunately, Lisp syntax is extremely
simple. Unfortunately, you can't just type `x = whatever` and go on to the next
line like in the other languages we've seen up until now.

It's very different.

## Setup

Find and download CLISP for windows (or run `sudo apt-get install sbcl` 
on Ubuntu). When you open a new command line and type `clisp`, you ought 
to see a prompt. Typing `(quit)` exits.

To run a project, make a new text file called `test.lisp`, and type

    (print (+ 2 2))

and save it; then from the command line in the same directory, run 
`clisp test.lisp`.
