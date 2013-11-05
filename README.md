clojure-koans
=============

My solutions to [Clojure Koans](https://github.com/functional-koans/clojure-koans). 


I've reformatted all the koan source files <code>/src/koans/*.clj</code> in order to evaluate 
each koan in LightTable.

To run the source files in LightTable:

1. Open files in LightTable.
2. Open the command pane with <code>CTRL + SPACE </code>.
3. Type 'inst,' then choose 'Instarepl: Make current editor an instarepl.'


To run the source files with a Clojure REPL in your shell:

1. In each source file, before the start of the first koan, add the line <code>(meditations</code>.
2. Add a corresponding closing paren <code>)</code> to the last expression in the file. 
3. <code>cd</code> into clojure-koan directory.
4. Run <code>lein koan run</code>.
