# tec-FORTH

![](https://github.com/SteveJustin1963/tec-FORTH/blob/master/forth3d-1.png)

# Abstract
Forth, TEC-1, Z80, 

# Introduction 

Our honorary genius, John Hardy has developed "Firth of Forth" [F0F] (2019) for the TEC-1. This project is to test and confirm this powerful system. Trust me!

# Observe and Question 
* Is "Firth of Forth" a viable and robust Forth?
* Review the technical manual and expand until comprehensively complete.

 
# Theory - testable
* Test and report any bugs back through git. 


# Prediction
* "This is where the project gets interesting but nothing is ever smooth sailing, it's always hard" (Hardy 2020)

# Method 

* Need Serial IO

Code for BitBang (Robertson 2019) in Zip archive, not released yet.

Code "tec-BANG" not ready (Justin 2020).

Bens Serial IO addon https://github.com/SteveJustin1963/tec-SERIAL-BG not avail, he is developing it into Video card, TBA (Gremmett 2019)

* Need UART
"Firth is designed to run using a Motorola 6850 ACIA serial chip mapped to ports $80 and $81 (or 0x80 and 0x81) as per the hardware arrangement designed by Grant Searle." (Hardy 2020)

Use https://github.com/SteveJustin1963/tec-APUS , driver is experimental, but F0F can dive UART part.

* Load F0F into TEC-1

https://github.com/jhlagado/firth

https://github.com/SteveJustin1963/tec-BOOT not ready

Install ROM Emulator, https://github.com/SteveJustin1963/tec-ROM-EM-BG, for easy code loading. 


# Test
* JH internal tests
* Standard benchmark tests  
* Figforth, gforth, Peter Forth, etc
* Function test
* AM9511
* Forth Scientific Library

# Report, figures, tables

# Results

# Discuss objectively, scientific significance 

# Conclusion 

# Acknowledgements

https://www.facebook.com/jhlagado

https://www.facebook.com/otherunicorn

https://en.wikipedia.org/wiki/Charles_H._Moore

# References

Hardy, John 2020, https://docs.google.com/spreadsheets/d/196W4LSZB3WT3BBj0CI_23vvdlKwxeybq7q1GpcKLlhA/edit#gid=0&range=A21

Robertson, Jim (2019) https://docs.google.com/spreadsheets/d/196W4LSZB3WT3BBj0CI_23vvdlKwxeybq7q1GpcKLlhA/edit#gid=756830046&range=A2 

Justin, Steve "tec-BANG", https://github.com/SteveJustin1963/tec-BANG

Gremmett, Benn 2019, https://docs.google.com/spreadsheets/d/196W4LSZB3WT3BBj0CI_23vvdlKwxeybq7q1GpcKLlhA/edit#gid=1031750592&range=A4

https://en.wikipedia.org/wiki/Forth_(programming_language)

https://en.wikipedia.org/wiki/Firth

# Iterate, new hypotheses or predictions

Squeezing into ROM could lead to a mini Monitor (Hardy 2020)

Not enough RAM. TEC-1D upgrade for more ram and rom
https://github.com/SteveJustin1963/TEC-1D

Apply https://code2flow.com/ to code and add to manual



