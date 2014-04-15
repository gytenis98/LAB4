LAB4
====
#ALU
###ALU Schematic 

![alt text](http://s27.postimg.org/a0l3aeehv/2014_04_14_22_05_08.jpg)

###ALU Functionality 

| OpSel| Function 
|:----:|:----
| 0 | AND
| 1 | NEG
| 2 | NOT
| 3 | ROR
| 4 | OR
| 5 | IN 
| 6 | ADD
| 7 | LDA

###ALU Coding
ALU was built to perform 8 following commands: AND, NEG(2s complement), NOT(invert), ROR, OR, IN, ADD, LDA. To create these codes it took me one line per funtion. 

###ALU Simulation

![alt text](https://raw.githubusercontent.com/gytenis98/LAB4/master/Capture.JPG)

The simulation ran successfully. I checked each value of OpSel with corresponding value of Accumulator and Data and everything matched. 

![alt text](https://raw.githubusercontent.com/gytenis98/LAB4/master/Datapath_screen.JPG)
