<!--
.. title: Simple BF Interpreter in Racket
.. slug: simple-bf-interpreter-in-racket
.. date: 2026-06-03 16:14:47 UTC+02:00
.. tags: coding,racket,lisp,repo
.. category: project
.. link: 
.. description: a simple brainfuck interpreter done in Racket
.. type: text
-->

## A simple Brainfuck interpreter in Racket


I’ve been learning Racket as my Lisp of choice and, after a lot of
fiddling and small scripts, I realized that I still used other
languages (Python, Java, ...) to make more "serious" things so I wanted
to push myself with a slightly more difficult toy project. I was inspired by
[this](https://robertheaton.com/2018/12/08/programming-projects-for-advanced-beginners/)
list of advanced beginners projects. The inspiration for the
interpreter came from
[this](https://github.com/davecom/ComputerScienceFromScratch/tree/main/Brainfuck)
repository for a book from *No Starch Press* so I re-implemented the
minimal Brainfuck interpreter using the python code as guideline in
Racket to practice Racket’s syntax and functional style.


The code is intentionally small and well commented, so it can be read and
easily understood in its design choices (parsing, command dispatch,
and loop matching) and another beginner can use it as a reference or a
starting point for his own learning.

To cut to the chase, here is the [link](https://github.com/drasken/SimpleBrainfuckInterpreter/blob/main/main.rkt).