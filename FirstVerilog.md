Lab Summary
In this lab we learned our way around Vivado and how to write some basic Verilog code. We wrote a code for a basic on and off switch, an and gate, and an or gate. 
Then used that code to program a small board so we could get a physical representation of our code. We learned about the development environment Vivado and got 
experience with simulation and how it works.Also with connecting a board and running our code through it. 
Lab Questions

1 - Describe the stages of building a Verilog project in Vivado.
First you start by creating the project in the menu of the Vivado program. Then you name the project and choose its location in a subdirectory. 
You will then choose some basic project information like specifying sources and project type. After that you add files to your project which can be
customized to be used as sources for different things. Next you add constraints which set boundaries for what values should be assigned to meet 
conditions. After you have built the project you are ready to write your logic code, and export it onto your board.

2 - What is the value in looking at the elaborated design schematic?
It gives you a good visual representation of your circuit. It shows you all your different gates that your circuit is using.
This can be used to visualise how your gates will connect to each other which can be useful for error handling and debugging. 
This also helps to learn the circuit better as you can see it laid out with an image instead of just seeing the logic written in code. 

3 - Why should we simulate our designs frequently? What does the simulation do?
This ensures that we do not have any bugs in our code at any step of the development process. If we simulate after each new piece
we add to our logic then we will know for sure what code is causing the issue. The simulation generates a “net list” which describes 
the output of your logic in readable format. This allows you to understand your code better as well because ti tells you exactly what is happening.
