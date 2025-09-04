# EXPERIMENT--01-ALP-FOR-8086
## Name :SANJAY T

## Roll no: 212222110039

## Date of experiment :29.08.2025

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







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AL, 53H;

MOV BL, 24H;

ADD AL,BL;

HLT
```

## Output  
<img width="1145" height="668" alt="image" src="https://github.com/user-attachments/assets/0138943b-6ead-4624-86ef-1811178edf08" />


## Subtraction   of 8 bit numbers  ALP 
 ``` MOV AL, 53H;
 
 MOV BL,24H;
 
 SUB AL,BL;
 
 HLT
 ```
## Output
<img width="1373" height="649" alt="image" src="https://github.com/user-attachments/assets/82ce61cf-664e-47de-b6e4-57fdd7b11f6d" />
## multiplication of 8 bit numbers ALP
``` MOV AL, 53H;

MOV BL, 24H;

MUL BL;

HLT
```
 ## Output  
<img width="1227" height="599" alt="image" src="https://github.com/user-attachments/assets/ea03c486-027c-43c2-a8e6-6a7a4679168c" />



## Division alp 
``` MOV AL, 53H;

MOV BL, 24H;

DIV BL;

HLT
```
## Output  
<img width="1237" height="655" alt="image" src="https://github.com/user-attachments/assets/55581a64-fdd3-4bb0-a800-5455ede69cf2" />

 
## AND
```MOV AL, 53H;

MOV BL, 24H;

AND AL,BL;

HLT
```
## Output 
<img width="1222" height="620" alt="image" src="https://github.com/user-attachments/assets/6136b03d-6c18-4ac3-a531-38e805c35b4c" />


## OR
``` MOV AL, 53H;

MOV BL, 24H;

OR AL, BL;

HLT
```
## Output
<img width="1318" height="571" alt="image" src="https://github.com/user-attachments/assets/02ee1ffc-d315-4e32-a203-efacb05f113b" />


## NOT
``` MOV AL, 53H;

MOV BL, 24H;

NOT AL;

HLT
```
## OUTPUT

<img width="1230" height="645" alt="image" src="https://github.com/user-attachments/assets/1822dc7c-0bcd-40e2-8f3a-643f10918acc" />

## EX-OR
```
MOV AL, 53H;

MOV BL, 24H;

XOR AL, BL;

HLT
```
## OUTPUT
<img width="1182" height="654" alt="image" src="https://github.com/user-attachments/assets/c054eeda-6fc9-4408-95b0-192685325756" />


## NAND 
```
MOV AL,53H
MOV BL,24H
AND AL,BL
NOT AL

```


##  OUTPUT
<img width="1163" height="598" alt="image" src="https://github.com/user-attachments/assets/4e0fbe21-c3ee-4b7c-a7cf-c93da43a8c5a" />


## Result :
 Thus ,ALP for fundamental arithmetic and logical operations are executed successfully.








