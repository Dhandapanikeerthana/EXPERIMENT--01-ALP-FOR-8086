# EXPERIMENT--01-ALP-FOR-8086
Name : KEERTHANA D

Roll no : 212224040155

Date of experiment : 20-08-2025





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
Mov ax,0801h;

Mov bx,8122h;

add ax,bx;

hlt
```


## Output 
<img width="1920" height="1080" alt="Screenshot (103)" src="https://github.com/user-attachments/assets/ffe0f5e3-7d41-4643-b626-db0e81dc1ffa" />

 
## Subtraction   of 8 bit numbers  ALP 
```
Mov al,86h;

Mov bl,98h;

sub al,bl;

hlt
```
## Output  
<img width="1920" height="1080" alt="Screenshot (102)" src="https://github.com/user-attachments/assets/90d6365d-fed6-4bff-b7f3-479163e9611c" />

## Multiplication alp 
```
Mov a,1485h;

Mov bx,8122h;

mul bx;

hlt
```

 ## Output  
 <img width="1920" height="1080" alt="Screenshot (104)" src="https://github.com/user-attachments/assets/6fb1183d-81ab-4b86-a907-663474ea7eaf" />



## Division alp 
```
Mov al,98h;

Mov bl,88h;

div bl;

hlt
```


## Output  
<img width="1920" height="1080" alt="Screenshot (105)" src="https://github.com/user-attachments/assets/772c3efd-85bd-48b5-8cc3-3fd908de3912" />


## Programs for logical operations

## AND alp
```
Mov al,98h;

Mov bl,88h;

and al,bl;

hlt
```

## Output


<img width="1920" height="1080" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/efcae1e0-e7c0-489c-91b1-94f236068fae" />

## OR alp
```
Mov al,53h;

Mov bl,68h;

or al,bl;

hlt
```
## Output


<img width="1920" height="1080" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/02f8ee59-ef89-4656-9fd4-df28f743988e" />


## XOR alp
```
Mov al,43h;

Mov bl,40h; 

xor al,bl;

hlt
```

## Output

<img width="1920" height="1080" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/f3868a32-c343-4820-b1f5-12b3b996b83f" />



## NOt
```
Mov al,43h;

Mov bl,66h;

not al;

hlt
```

## Output


<img width="1920" height="1080" alt="Screenshot (112)" src="https://github.com/user-attachments/assets/79c554cf-ecae-4320-8fc6-20607378aec0" />


## Result :
 Thus, ALP for fundamental arithmetic and logical operations are executed successfully








