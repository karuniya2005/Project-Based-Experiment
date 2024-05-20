### Project-Based-Experiment

**AIM:**

To design and simulate the traffic light controller.

**SOFTWATE USED:**

Quartus II

**THEORY:**
	
     	Consider a controller for traffic at the intersection of three main roads.  

  ![image](https://github.com/naavaneetha/Project-Based-Experiment/assets/154305477/e3af03dd-a4de-4b21-af0a-a5a332a3e4b6)


 The traffic signal for all the three main roads have equal priority and they remain red by default.

 In state 00,the traffic signals remains red for first five counts and yellow of road1 turns on for the next four counts.

 In state 01, the green of road1 turns on for first five counts and yellow of road1 and road2 turns on for next four4 counts of this state.
 
 In state 10, the traffic signal of road1 comes back to the red and that of road2 goes to green for tee first five counts.For the next four counts the traffic signal of road2 and road3 remains yellow.


 In state 11, the traffic signal of road2 comes back to the red and that of road3 goes to green for the first five counts.For the next four counts the traffic signal of road3 turns to yellow

 At the end of four states,the traffic signal of all the three roads come back to red.

**Task Assigned**

From the HDL code given formulate the correct code  to divert the traffic to path 1 direction and disable the control in other directions (Assume user is at MR3 spot)

**Procedure**

1.	Type the program in Quartus software.
2.	Compile and run the program.
3.	Generate the RTL schematic and save the logic diagram.
4.	Create nodes for inputs and outputs to generate the timing diagram.
5.	For different input combinations generate the timing diagram
   
**Program:**

**Program to implement the given logic function and to verify its operations in quartus using Verilog programming.**

**Developed by:KARUNIYA M**

**RegisterNumber:212223240068**

![332012653-8418fb23-7ab9-4af3-9975-7f874dd1f26c](https://github.com/karuniya2005/Project-Based-Experiment/assets/161425769/35fd6b9b-e5cb-4ce7-978a-2749496c28d3)

![332012753-c498c5d7-e1c6-49bd-b47f-60ada74530a3](https://github.com/karuniya2005/Project-Based-Experiment/assets/161425769/140854a6-9a35-4ec3-9aeb-b5d5d4183963)


**RTL Schematic**

![332006465-d36f278f-247c-4045-a969-7e21fc44b520](https://github.com/karuniya2005/Project-Based-Experiment/assets/161425769/77c43ad4-7f51-474d-9018-cc5a0beeee83)

**Output Timing Waveform**

![332007437-62636ae7-45c4-45c3-adf7-444c4ec349b5](https://github.com/karuniya2005/Project-Based-Experiment/assets/161425769/2452338d-3c0d-49c5-b288-3f0649d49232)


**Result:**
 Thus the program executed successfully.




