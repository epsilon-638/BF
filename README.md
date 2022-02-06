## BF Intepreter written in Racket
### Following along in https://beautifulracket.com/bf
```racket
#lang reader "reader.rkt"
++++++[>++++++++++++<-]>.
>++++++++++[>++++++++++<-]>+.
+++++++..+++.>++++[>+++++++++++<-]>.
<+++[>----<-]>.<<<<<+++[>+++++<-]>.
>>.+++.------.--------.>>+.
```
#### Output:
```
Hello, World!
```
#### To anyone who doesn't know what BF is, it's one of the most famous Esoteric Languages. It is designed around the idea of minimalism. BF is a turing complete stack oriented language with only 8 operators.

### Operators
- `<` : Moves the pointer of the stack to the left
- `>` : Moves the pointer of the stack to the right
- `+` : Increments the current memory cell
- `-` : Decrement the current memory cell 
- `[` : Beginning of a loop, if current cell = 0 it breaks out
- `]` : Go back to beginning of loop if cell != 0 
- `.` : Display char at current cell
- `,` : Input a char at current cell

#### This proj is a section of the book Beautiful Racket which introduces the paradaigm of laguage-oriented programming by Mattew Butterick found [''here'](https://beautifulracket.com/).  
