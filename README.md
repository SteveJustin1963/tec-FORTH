
 
![](https://github.com/SteveJustin1963/tec-FORTH/blob/master/pics/forth3d-1.png)

 
Investigate and test John Hardy’s brilliant https://github.com/jhlagado/firth forth code for the TEC-1 


 

![](https://github.com/SteveJustin1963/tec-FORTH/blob/master/forth3d-1.png)

We don't care if ye-olde circa 1983 TEC-1 with a Z80 engine only has 2k ROM + upto 14k RAM, never seen a UART, 9511, CTC, SIO, DMA, PIO and DART, GPIO and blah-blah, hey “there's still a lot more that could and will be done with this design without deviating too much from the spirit of the original TEC-1” (John Hardy & Ken Stone). 

Now with the TEC1-D, “We only need to design a small amount of interfacing circuitry and the balance achieved with a program… to promote machine code programming and learn the operation of control circuits. It's a continuing fully-fledged applications machine, with a micro operating system developed as a basic unit adapted to suit a wide range of specific situations...by installing some other language, we can give the TEC1, a native "language" for assembly code, to make programming easier [thats] all contained within the unit, at the cost of some RAM” [Ken Stone].  

Prof. John Hardy has developed "Firth of Forth" (2019) for Z80 SBC such as the TEC-1. "I think people need to write more assembly language to appreciate the power of Forth. It's actually the solution to many problems but it requires exposure to those problem to understand them. Forth is the highest level solution for 8 bit. C language requires 16 bit architectures at a minimum." (John Hardy 2020). This project is to test and confirm this powerful system. 

Lets try John Hardy's “Firth of Forth” on the TEC-1. A good move because Forth has “an easy syntax, is extensible, modular and permits significant programming, in an environment that combines a concatenative compiler with an interactive shell, it's a threaded interpretive language for machine coding; and without recompiling; it can run in 4k of RAM; it’s used in science, physics, astronomy, even NASA. It just needs a serial port say 6850 or at least bitbang serial and add 6k of RAM.  An optional AM9511 maths chip can be added as well. 
