# tec-FORTH

![](https://github.com/SteveJustin1963/tec-FORTH/blob/master/forth3d-1.png)

# Abstract
Forth, TEC-1, Z80, 

# Introduction 

Our honorary genius, John Hardy has developed "Firth of Forth" [FoF] (2019) for the TEC-1. This project is to test and confirm this powerful system. Trust me!

# Observe and Question 
* Is "Firth of Forth" a viable and robust Forth?
* Review the technical manual and expand until comprehensively complete.

 
# Theory - testable
* Test and report any bugs back through git. 


# Prediction
"This is where the project gets interesting but nothing is ever smooth sailing, it's always hard" (Hardy 2020)

# Method 

## Load Forth into TEC-1
1. BitBang and file hex transfer in Zip archive, n.a. (Robertson 2019).
2. Code for "tec-BANG" n.a. (Justin 2020).
3. Serial IO addon https://github.com/SteveJustin1963/tec-SERIAL-BG n.a. (Gremmett 2019).
3. Serial on Video card, https://github.com/SteveJustin1963/tec-VIDEO-BG n.a. (Gremmett 2019).
4. Tec-Boot, https://github.com/SteveJustin1963/tec-BOOT n.a. (Justin 2020).
5. ROM Emulator, https://github.com/SteveJustin1963/tec-ROM-EM-BG, ready!
6. Transfer https://github.com/jhlagado/firth to TEC-1. 
7. "Firth is designed to run using a Motorola 6850 ACIA serial chip mapped to ports $80 and $81 (or 0x80 and 0x81) as per the hardware arrangement designed by Grant Searle." (Hardy 2020). 
8. Arithmetic Processing Unit with AM9511 and Serial IO MC68B50P, https://github.com/SteveJustin1963/tec-APUS, ready!

# Test
Boot !
1. JH internal tests
2. Standard benchmark tests  
3. Figforth, gforth, Peter Forth, etc
4. Function test
5. AM9511
6. Forth Scientific Library

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

1. Update manual with all findings, make it comprehensive! 
Use https://code2flow.com/ to also explain code in flow-chart.
2. Squeezing into ROM could lead to a mini Monitor (Hardy 2020)
3. ROM version of Forth, 2k not enough. Redesign, eg, Redesign with 8k ROM +56K RAM per Grant Searle.
https://github.com/SteveJustin1963/TEC-1D





