This zip file contains a calculator class in C# that handles
addition, subtraction, multiplication, division, UNDO, CLEAR, and EXIT.

The only method that should be called directly is the calculate method.
The calculate method passes a string in the format of "real-literal operation real-literal"
or UNDO, CLEAR, and EXIT can be passed as well. 

The calculator class also utilizes a stack to hold a running total
this running total can be manipulated by running mathematical expressions
or by running the UNDO or CLEAR methods.

Note that the running total value is equal to the sum of all the outputs of the mathematical expressions
i.e.
2 + 2
returns 4(running total: 4)
6 - 3
returns 3(running total 7)

The main method in the .zip contains an example of how to use the calculator
The main method is also localized in English, French, and Thai.
