# Name : SANJAY T
# Roll no : 212222110039
# Date of experiment : 29-08-2025





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations :

## Addition of 8 bit ALP : 
```
MOV AX,[3001H]
MOV BX,[3003H]
ADD AX,BX
JNC Loop
INC CL
Loop:
MOV [3005H],AX
MOV [3007H],CL
HLT
```
## Output :  
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d6f25e19-2b93-46e5-9079-ae82cdbcaa0d" />


## Subtraction of 8 bit numbers  ALP : 
```
MOV AX,[3001H]
MOV BX,[3003H]
SUB AX,BX
JNC Loop
INC CL  
NOT AX
INC AX
Loop:
MOV [3005H],AX
MOV [3007H],CL
HLT
```
## Output:
![IMG-20250829-WA0007](https://github.com/user-attachments/assets/868040e3-3577-49b4-a30b-5a555d97b95d)

## Multiplication ALP:
```
MOV CL,00
MOV AX,[3001H]
MOV BX,[3003H]
MUL BX
MOV [3005H],AX
MOV [3007H],DX
HLT
```
## Output :
![IMG-20250829-WA0009](https://github.com/user-attachments/assets/e5804be9-0f00-467e-9576-189ee1d56961)

## Division ALP :
```
MOV CL,00
MOV AX,[3001H]
MOV BX,[3003H]
DIV BX
MOV [3005H],AX
MOV [3007H],DX
HLT
```
## Output :
![IMG-20250829-WA0006](https://github.com/user-attachments/assets/62ab8b2a-d3c5-446b-8872-c81ca66b8fae)

## AND ALP :
```
MOV AX,[3001H]
MOV BX,[3003H]
AND AX,BX
MOV [3005H],AX
HLT
```
## Output :
![and](https://github.com/user-attachments/assets/d5e6655a-3541-4176-97a1-a0dafa5a6515)

## OR ALP :
```
MOV AX,[3001H]
MOV BX,[3003H]
OR AX,BX
MOV [3005H],AX
HLT
```
## Output :
<img width="1643" height="1009" alt="Screenshot 2025-08-29 153434" src="https://github.com/user-attachments/assets/20bedf3c-7d1f-4453-851e-31225aa4d384" />

## NOT ALP :
```
MOV AX,[3001H]
NOT AX
MOV [3003H],AX
HLT
```
## Output :
![IMG-20250829-WA0016](https://github.com/user-attachments/assets/1b36c542-e28d-4e8d-8b83-80e8fb607aec)

## NAND ALP :
```
MOV AX,[3001H]
MOV BX,[3003H]
AND AX,BX
NOT AX
MOV [3005H],AX
HLT
```
## Output :
<img width="1591" height="986" alt="Screenshot 2025-08-29 153943" src="https://github.com/user-attachments/assets/c0de3ea0-46be-4c32-9c8b-b99da278ad4d" />

## NOR ALP :
```
MOV AX,[3001H]
MOV BX,[3003H]
OR AX,BX
NOT AX
MOV [3005H],AX
HLT
```
## Output :
<img width="1587" height="984" alt="Screenshot 2025-08-29 153558" src="https://github.com/user-attachments/assets/89262610-0b94-49b3-9621-0697b0746ac3" />

## XOR ALP :
```
MOV AX,[3001H]
MOV BX,[3003H]
XOR AX,BX
MOV [3005H],AX
HLT
```
## Output :
![IMG-20250829-WA0017](https://github.com/user-attachments/assets/a68ed9db-0445-4937-9743-16311d385d0d)

## XNOR ALP :
```
MOV AX,[3001H]
MOV BX,[3003H]
XOR AX,BX
NOT AX
MOV [3005H],AX
HLT
```
## Output :
![IMG-20250829-WA0018](https://github.com/user-attachments/assets/3898b85b-879f-4993-920d-4a92e21a7607)

## Truth Table for LOGIC GATES :
![TT](https://github.com/user-attachments/assets/aedbc752-c356-43e2-a72b-b41a39247a6d)

## Result :
Thus the program is verified and the desired output is got.








