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

#####Functionality 

| Function | Operation
|:----:|:----
| AND  | A<- A and M[aaaa aaaa]
| NEG  | A<- -A
| NOT  | A<- not (A)
| ROR  | A<- ror (A)
| OR   | A<- A or M[aaaa aaaa]
| IN   | A<- I[aaaa]
| ADD  | A<- A + M[aaaa aaaa]
| LDA  | A<- M[aaaa aaaa]

#Datapath Shell

![alt text](https://raw.githubusercontent.com/gytenis98/LAB4/master/Datapath_screen.JPG)

#####Analysis
I checked my datapath the same way I checked my ALU testbench. I manually checked all the possible combinations and compared to calculations performed with a pen in my notebook. After this not very quick check I found that my datapath performed as expected.

#####Bugs and Errors
I made only one small mistake which at first did not let me to get "Check" at the syntax part. Instead of `elsif` I wrote `elseif` in three parts. 
