# ASM-RISK-V_Sublime-Text-3_Syntax-Highlighting
This is a small syntax highlighting package for the assembly language RISK-V that I had to use for University.
It has been made on and for Sublime Text 3, I don't know how compatibilities works.

## Dependencies
This has been developped through the norm introduded with Build 3084 and hence needs : [PackageDev](https://github.com/SublimeText/PackageDev)

## Installation
For Windows, setup install, place the file RISK-V_Assembly.sublime-syntax file in the folder
`"C:\Users\$USER\AppData\Roaming\Sublime Text 3\Packages\User"`
I havn't tried Unix or Local install, but I'm sure it would be easy to find.

## Disclaimer
This package is not meant to be complete, nor respecting any Syntax Highlighting norms. It has been made by hand adding functions that I was using to make the code readable. The norms used for the highlights were pretty much intuitive.
I developped this for a personal use. Feel free to use or modify this base to complete it.

## Color mapping
```
Purple : Numerical values
Red : Labels
Green : Registers
Blue : Functions
Orange : Branches / Jumps
White : I/O, brackets (and parameters that I didn't managed to highlight)
Grey : Comments
```
Here a small example of a factorial function :
```
```
![alt text](https://github.com/Neah-Ko/ASM-RISK-V_Sublime-Text-3_Syntax-Highlighting/blob/master/RISK-V_ex.jpg "RISK-V ASM Factorial")
