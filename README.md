Math Compiler
=============

The idea of this program is to take a string of numbers, say 1 + 1, tokenise it, compile the result and return the answer.  

Format will be: 

number <space> <symbol +/-*> number <space> <additional symbols> number

It should be able to deal with any number of operations, and take in to account order precedence too. 

It will also handle parentheses as well to change order precedence, and it will tokenise and compile these first, and reformat the string on the fly.  

Compile
=======

git clone repo

cd math_compiler

mkdir build

cmake ..

make

./math_compiler 4 + 5 * (9 + 8) 

It should return the correct value which is 94 in the above example.