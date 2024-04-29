# AIM
To design and simulate Priority Encoder using vivado 2023.2.
# Software Required:
vivado 2023.2 software.

# Procedure:
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
# PRIORITY_ENCODER
![image](https://github.com/RESMIRNAIR/PRIORITY_ENCODER/assets/154305926/016b3b20-1d4d-48fd-9012-a2c725b822db)
# Truth Table
![image](https://github.com/RESMIRNAIR/PRIORITY_ENCODER/assets/154305926/3da43bab-6ee6-456f-858f-4553d3623f8c)
# PROGRAM
```
module encoder(d,a,b,c);
input [7:0]d;
output a,b,c;
or(a,d[4],d[5],d[6],d[7]);
or(b,d[2],d[3],d[6],d[7]);
or(c,d[1],d[3],d[5],d[7]);
endmodule
```
# OUTPUT

![image](https://github.com/j-gugan/PRIORITY_ENCODER/assets/163828735/141f8d43-87d9-4419-a6b5-c857732e40de)
# RESULT
Thus,the priority encoder using vivado 2023.2 is simuated and synthesised.
