clojure-koans
=============

My solutions to [Clojure Koans](https://github.com/functional-koans/clojure-koans). 


I've reformatted all the koan source files (/src/koans/*.clj) so that I can evaluate 
each koan in LightTable.

To run the source files in LightTable:

1. Open files in Light Table
2. Open the command pane (CTRL + SPACE) and type 'inst' then choose 'Instarepl: Make current editor an instarepl'


To run the source files in your shell:

1. In each source file, before the start of the first koan, add a line (meditations
2. Add a corresponding closing paren ) to the last expression in the file. 
3. cd into clojure-koan directory 
4. $ lein koan run
