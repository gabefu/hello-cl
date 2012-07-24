hello-cl
========

Basic Common Lisp project to learn Lisp syntax and lack thereof.

#### Todo

Read pages 3-8 in Paradigms of Artificial Intelligence Programming.
Make a file called `paip1-1.lisp` that, when run, outputs any old thing
you've learned from those pages.

#### Resources

Don't get intimidated. :)

Aside from googling for tutorials, introductions, etc, 
Check out the first few chapters in the following books:

- ANSI Common Lisp
- On Lisp (chapter 2, for instance)
- __Paradigms of Artificial Intelligence Programming: Case Studies in 
  Common Lisp__ (PAIP for short). Actually, this is the least scary
  for now!

#### Setup

Find and download CLISP for windows (or run `sudo apt-get install sbcl` 
on Ubuntu). When you open a new command line and type `clisp` (or `sbcl` 
in Ubuntu), you ought to see a prompt. Typing `(quit)` exits.

To run a project, make a new text file called `test.lisp`, and type

    (print (+ 2 2))

and save it. Then from the command line in the same directory, run 
`clisp test.lisp`.
