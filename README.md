# SIC-XE-Assembler
Assembler for SIC-XE. Course project for CSN-252.
## Introduction
- SIC/XE stands for Simplified Instructional Computer Extra Equipment or Extra Expensive. 
This is particularly the advanced version of SIC, both of which are closely related and is upward 
compatible as well. 
- Memory: It is made up of 8-bit bytes and the memory size is 1 megabyte (230 bytes). The 
memory size difference between SIC AND SIC/XE leads to a change in the instruction formats 
and more versatile addressing modes in SIC/XE. 1 word in SIC/XE architecture comprises 24 bits or 3 bytes. The entire addressing is based on byte addressing and word addresses are specified by their lower-order bits. 
- Data Formats (SIC/XE): Characters are stored/represented as per their ASCII codes (American 
Standard Codes for Information Interchange) Integers are represented by Binary Numbers and 
floating point numbers (decimal values) using 48-bit formats as per IEEE.

## Details
- Input to assembler- Assembler source program using the instruction set of SIC/XE. 
- Assembler will generate the following files as output- <br>
  - Pass 1 will generate a Symbol Table. 
  - Pass 1 will also generate Intermediate File for the Pass 2. 
  - Pass 2 will generate a listing file containing the input assembly code and address, block number, object code of each instruction. 
  - Pass 2 will also generate an object program including following type of record: H, D, R, T, M 
and E types. 
  - An error file is also generated displaying the errors in the assembly program (if any). 
## Steps to compile and run
- Download and open the folder in VS code . 
- Compile pass2.cpp in the terminal using g++ pass2.cpp 
- Now a new file with the name pass2.exe or a.out will be created . 
- Create a new input file in the same folder say input.txt . 
- Now open terminal and give the command .\’pass2.exe’ , where pass2.exe can be replaced by the name of the file that was generated two steps back on compilation. 
- Now the assembler asks for the name of input file which is to be put as input.txt , press 
enter. Now files for pass1 and object files, etc will be created.
