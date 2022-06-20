# Computer From Scratch
A project aimed at building a modern computer bottom-up from scratch, including the following components:
 - Hardware Chipset
    - Circuitry and Logic Gates for Boolean Arithmetic
    - CPU (Central Processing Unit) 
    - ALU (Arithmetic Logic Unit)
    - RAM (Random Access Memory)
 - Low Level Programming
    - Machine Language
    - Assembly Language
 - Virtual Machine
    - VM Translator
 - High-Level Programming
    - Object Oriented Programming Language
    - Syntax Analysis and Code Generation
    - Compiler
 - Operating System.

# Hardware Chipset
The chipset designed for this computer, including the standard logic-gates, custom ALU, and random-access memory. Logic written and tested using HDL (hardware description language) by Nand2Tetris.

## How to use

Install [Nand2Tetris for VS Code](https://marketplace.visualstudio.com/items?itemName=roblourens.vscode-nand2tetris-hdl)
to open the .hdl files, and use the Nand2Tetris's Run Code feature to test the logic for a circuit (tests defined in .tst, and correct results in .cmp)

You can also use the online [falstad circuit simulator](http://www.falstad.com/circuit/) to run the .circuitjs.txt files to simulate the circuits.

## Circuit Designs
These are some of the designs implemented using the falstad circuit simulator, the logic for these can be found in the corresponding `.circuitjs.txt` files.

Arithmetic Logic Unit
![ALU](https://i.imgur.com/uyOP5xF.png)

Dmux
![DMux](https://i.imgur.com/i2oeImq.png)

DMux4way
![DMux4Way](https://i.imgur.com/TH1DaN4.png)

DMux8Way
![DMux8Way](https://i.imgur.com/2DQr3mK.png)

And
![And](https://i.imgur.com/FiB1May.png)

Or
![Or](https://i.imgur.com/QWb1TWh.png)

<hr>

*If you would like to complete this project yourself, make sure to check out the exemplary [nand2tetris](https://www.nand2tetris.org/) course.*