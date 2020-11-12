## Abstract
Forth, TEC-1, Z80, 

## Literature Review
https://dev.to/jhlagado/structured-programming-in-z80-assembly-554d

https://github.com/jhlagado/struct-z80

## Introduction 

![](https://github.com/SteveJustin1963/tec-FORTH/blob/master/pics/imf-tec-1.png)
![](https://github.com/SteveJustin1963/tec-FORTH/blob/master/pics/forth3d-1.png)

“Your mission Jim, should you decide to accept it is to; 
Investigate and test John Hardy’s brilliant https://github.com/jhlagado/firth forth code for the TEC-1 

You will have to add serial hardware from either the foillowing
* https://github.com/SteveJustin1963/tec-SERIAL-BG
* https://github.com/SteveJustin1963/tec-APUS 
* https://github.com/SteveJustin1963/tec-BANG

After you've mission, file a report to https://github.com/SteveJustin1963/tec-FORTH/wiki

This tape will self-destruct in five seconds. Good luck, Jim.” I.M.F.

![](https://github.com/SteveJustin1963/tec-FORTH/blob/master/pics/smoke-tape.png)

![](https://github.com/SteveJustin1963/tec-FORTH/blob/master/forth3d-1.png)

We don't care if ye-olde circa 1983 TEC-1 with a Z80 engine only has 2k ROM + upto 14k RAM, never seen a UART, 9511, CTC, SIO, DMA, PIO and DART, GPIO and blah-blah, hey “there's still a lot more that could and will be done with this design without deviating too much from the spirit of the original TEC-1” (John Hardy & Ken Stone). 

Now with the TEC1-D, “We only need to design a small amount of interfacing circuitry and the balance achieved with a program… to promote machine code programming and learn the operation of control circuits. It's a continuing fully-fledged applications machine, with a micro operating system developed as a basic unit adapted to suit a wide range of specific situations...by installing some other language, we can give the TEC1, a native "language" for assembly code, to make programming easier [thats] all contained within the unit, at the cost of some RAM” [Ken Stone].  



## Observe and Question 

Prof. John Hardy has developed "Firth of Forth" (2019) for Z80 SBC such as the TEC-1. "I think people need to write more assembly language to appreciate the power of Forth. It's actually the solution to many problems but it requires exposure to those problem to understand them. Forth is the highest level solution for 8 bit. C language requires 16 bit architectures at a minimum." (John Hardy 2020). This project is to test and confirm this powerful system. 

Lets try John Hardy's “Firth of Forth” on the TEC-1. A good move because Forth has “an easy syntax, is extensible, modular and permits significant programming, in an environment that combines a concatenative compiler with an interactive shell, it's a threaded interpretive language for machine coding; and without recompiling; it can run in 4k of RAM; it’s used in science, physics, astronomy, even NASA. It just needs a serial port say 6850 or at least bitbang serial and add 6k of RAM.  An optional AM9511 maths chip can be added as well. 


## Theory - testable
"Forth is a simple, yet extensible language; its modularity and extensibility permit writing significant programs. A Forth environment combines the compiler with an interactive shell, where the user defines and runs subroutines called words. Words can be tested, redefined, and debugged as the source is entered without recompiling or restarting the whole program. All syntactic elements, including variables and basic operators, are defined as words. Forth environments vary in how the resulting program is stored, but ideally running the program has the same effect as manually re-entering the source." (wiki)

Historically Forth has proven itself in machine control over 50 years. Firth of Forth can also.
* To prove its a viable and robust system
* Review and expand it technically until comprehensively complete.


## Prediction
"This is where the project gets interesting but nothing is ever smooth sailing, it's always hard" (John Hardy 2020)

Forth will make the tec-1 easier to use, faster and more powerful.

## Method 

1. Install working serial port addon to TEC-1.
* "Firth is designed to run using a Motorola 6850 ACIA serial chip mapped to ports $80 and $81 (or 0x80 and 0x81) as per the hardware arrangement designed by Grant Searle." (Hardy 2020). 
* Serial HW
  * Consider https://github.com/SteveJustin1963/tec-BANG ...NA
  * Consider https://github.com/SteveJustin1963/tec-SERIAL-BG ...Yes March 2020
  * Consider https://github.com/SteveJustin1963/tec-VIDEO-BG with serial ...NA
  * Consider https://github.com/SteveJustin1963/tec-APUS ...under construction

2. Transfer Forth .bin to TEC-1 and run
* Code setup
  * Source https://github.com/jhlagado/firth 
  * Configure RAM ROM settings in main.Z80
  * Compile and extract .bin
* Transfer
  * Consider https://github.com/SteveJustin1963/tec-BOOT ...NA
  * Consider https://github.com/SteveJustin1963/tec-ROM-EM-BG ...yes...try

3. Testing
* Confirm in asm80.com
  * https://github.com/jhlagado/firth#Listing-words
* Terminal tests
* Science test https://github.com/SteveJustin1963/tec-FORTH-SCIENTIFIC
* AM9511 test 
* Test code from different sites
 * https://jupiter-ace.co.uk/index.html
 * https://sites.google.com/site/libby8dev/fignition

##  Journal
see wiki



## Report, figures, tables

## Results

## Discuss objectively, scientific significance 

## Conclusion 

## Acknowledgements

https://www.facebook.com/jhlagado

https://www.facebook.com/otherunicorn

https://en.wikipedia.org/wiki/Charles_H._Moore

## References
https://en.wikipedia.org/wiki/Forth_(programming_language)

https://en.wikipedia.org/wiki/Firth

http://pygmy.utoh.org/3ins4th.html


## Iterate, new hypotheses or predictions
* flowchart Johns code
* Squeeze code down to 4k, 2k, 1k 
* https://github.com/jhlagado/SerMon
* ideas from http://www.w3group.de/stable_glossar.html 

Many new Forth projects can be explored more easily such as;
* controlling a telescope and connecting to star maps
* play with AI and resonating circuits and expand into robotics 


