# EXPERIMENT--01-ALP-FOR-8086
## Name : HARSHAt G
## Roll no : 212224040106
## Date of experiment : 22-04-2026





## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
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
MOV AX,132H;
MOV BX,362H;
ADD AX,BX   
MOV [5000H],AX;
```
## Output  

<img width="1849" height="1080" alt="ADD" src="https://github.com/user-attachments/assets/9fd27dd6-ee73-49ef-90e3-de505c824906" />
 
## Subtraction   of 8 bit numbers  ALP 
```
MOV AX, 132H;
MOV BX, 362H;
SUB AX, BX     
MOV [5002H],AX;
```
## Output

<img width="1896" height="1080" alt="SUB" src="https://github.com/user-attachments/assets/e07887b6-8c71-4920-9b5e-3531cd71c860" />

## Multiplication alp 
```
MOV AX, 75H;
MOV BX, 32H;
MUL BX      
MOV [5004H],AX;
```
 ## Output  

<img width="1851" height="1058" alt="MUL" src="https://github.com/user-attachments/assets/dd7d5a14-9a04-4e1d-a9ed-2260d2781ca3" />

## Division alp 
```
MOV AX, 68H;
MOV BX, 18H;
DIV BX       
MOV [5006H],AX;
```
## Output  

<img width="1795" height="1095" alt="DIV" src="https://github.com/user-attachments/assets/3c939d35-9873-404a-ac5b-434519e96ed9" />

## Programs for logical  operations
## AND 
```
MOV AX,6132H;
MOV BX,8362H;
AND AX,BX   
MOV [5000H],AX;
```
## OUTPUT:

<img width="1873" height="1069" alt="image" src="https://github.com/user-attachments/assets/b3d77622-a655-4cbd-a4c8-49afcc3e5be6" />

## OR
```
MOV AX, 4132H;
MOV BX, 2362H;
OR AX, BX     
MOV [5002H],AX;
```
## Output

<img width="1815" height="1078" alt="image" src="https://github.com/user-attachments/assets/51b0bbb3-82c9-4556-829f-b9f827b40b8f" />

## NAND:
```
MOV AX, 8475H;
MOV BX, 1232H;
AND AX,BX
NOT AX      
MOV [5004H],AX;
```
## Output
<img width="1870" height="1085" alt="image" src="https://github.com/user-attachments/assets/5576eef8-73dc-4450-bd2c-7b647196189e" />

## NOR
```
MOV AX, 4132H;
MOV BX, 2362H;
OR AX, BX  
NOT AX   
MOV [5006H],AX;  
```
## Output
<img width="1836" height="1016" alt="image" src="https://github.com/user-attachments/assets/271d02bc-d174-4831-b8a4-2ba356f7a942" />

## NOT
```
MOV AX, 5566H;
NOT AX        
MOV [5010H],AX;
```
## OUTPUT
<img width="1819" height="1027" alt="image" src="https://github.com/user-attachments/assets/8fca4b8e-0802-481e-ba13-08bd59b4129c" />

## XOR
```
MOV AX, 2233H;
MOV BX, 3344H;
XOR AX,BX
MOV [5012H],AX;
```
## Output
<img width="1863" height="1065" alt="image" src="https://github.com/user-attachments/assets/738a0cb5-30e6-4065-b9f8-6ff3de698eb5" />

## XNOR
```
MOV AX,3344H;
MOV BX,4455H;
XOR AX,BX
NOT AX
MOV [5014H],AX;
```
## Output
<img width="1832" height="1098" alt="image" src="https://github.com/user-attachments/assets/5f0f3558-c9f0-491d-81a6-a1b8adbfac23" />

## Result :
The Write and execute ALP on fundamental arithmetic and logical operations is executed successfully.







