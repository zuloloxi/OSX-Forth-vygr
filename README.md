# OSX-Forth
=========

Forth for OSX, bootstrap from x86 NASM then Forth only.

Build with:

nasm -f macho forth.nasm
ld -o forth -e _main forth.o

Run with:

./forth

On seeing the prompt enter WORDS to list all available words.

## Import [OSX-Forth](https://github.com/vygr/OSX-Forth) from [Chris Hinsley - vygr](https://github.com/vygr) repository.
