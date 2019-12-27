# NandtoTetris

This repo is the collection of all the projects of the course NandtoTetris. <br>
[Website Link](https://www.nand2tetris.org/software) <br>
[Coursera Link](https://www.coursera.org/learn/build-a-computer/home/welcome) <br>

## Installation instructions

Install the software suite containing all the necessary project tools and guidelines from [here](https://drive.google.com/file/d/1KcFPj8KQ_QAHheFmLCqs5iqC_0NCndvs/view).

## Week 1 - [Boolean_logic_functions_1](https://github.com/rushabh-mehta/nandtotetris/tree/master/Boolean_logic_functions_1)
We assume that Nand is the fundamental building block and use it as a starting point by abstracting away the implementation of "Nand".<br>
Once we design a function we can use it to design another functions (For e.g. once "Not" is designed it can be used to create "And").<br>
Designed following boolean functions in HDL:
<pre>
1. Not     7. Not16        13. Mux8Way16
2. And     8. And16        14. DMux4Way
3. Or      9. Or16         15. DMux8Way
4. Xor     10. Mux16
5. Mux     11. Or8Way
6. DMux    12. Mux4Way16
</pre>

## Week 2 - [Arithmetic logic unit_2](https://github.com/rushabh-mehta/nandtotetris/tree/master/Arithmetic_logic_unit_2)
<pre>
1. Designed a Half Adder, Full Adder and a 16 bit ripple carry adder.
2. Designed an ALU for the 16 bit HACK computer which has the following functionalities.
</pre>


ALU diagram             | ALU truth table
:-------------------------:|:-------------------------:
<img  src="https://github.com/rushabh-mehta/nandtotetris/blob/master/static/Hack_alu_diagram.png" width="100%" height="60%"> | <img src="https://github.com/rushabh-mehta/nandtotetris/blob/master/static/Hack_alu_truth_table.png" width="100%" height="60%"> 
