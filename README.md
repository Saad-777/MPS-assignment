# 4-Bit Microprocessor
Welcome to a 4-bit microprocessor Design on Stich.io by sebastian Lague
Following are the main instruction which our microprocessor will be able to execute along with their opcode
## Instruction Set
We took 4 bits as our Opcode
* Load Accumalator LDA 0000
* Add 0001
* Subtract 0010
* Out 0011
* HLT 1111
 ## Components
Main Components of our Microprocessor
* [Control Unit](#Control-Unit)
* [RAM](#RAM)
* [Program Counter](#Program-Counter)
* [Memory Address Register](#Memory-Address-Register)
* [B-Register](#B-Register)
* [Accumulator](#Accumulator)
* [Arithmetic Logic Unit (ALU)](#Arithmetic-Logic-Unit)
* [Output Register](#Output-Register)

## Control Unit

Some of the key functions of the CLU in a 4-bit microprocessor include:

### Instruction decoding:
The CLU decodes the opcode of the current instruction and generates the necessary control signals to execute the instruction.

### Address generation:
The CLU generates the address of the memory location where the next instruction or data is located.

### Data transfer:
The CLU controls the transfer of data between different parts of the processor, such as the registers, ALU, and memory.

### Control signal generation:
The CLU generates the control signals that control the operation of the processor, such as the clock signal and reset signal.

![CLU](https://user-images.githubusercontent.com/88718691/230791399-61bfdebd-0bbd-4914-ac46-2a1d47649dcf.png)

## RAM
In a 4-bit microprocessor, RAM typically consists of a small number of memory locations, each capable of storing 4 bits of data. The microprocessor can access any of these locations directly, without needing to read or write other locations first. This makes RAM an essential component for storing and manipulating data in a 4-bit microprocessor.

![RAM](https://user-images.githubusercontent.com/88718691/230791391-2f7d884d-ef66-4b41-a504-0da5d32e0229.png)

### Program Counter
 The program counter in a 4-bit microprocessor is a register that stores the memory address of the next instruction to be executed. It is automatically incremented after each instruction is executed, allowing the microprocessor to sequentially execute a series of instructions. The program counter is typically 4 bits wide, allowing it to address up to 16 memory locations in the microprocessor's memory space. The program counter is a crucial component for the proper functioning of a 4-bit microprocessor.
 
 ![Program COunter](https://user-images.githubusercontent.com/88718691/230791393-ffd1a674-d5c0-48da-bfe7-7af19aca6d9c.png)

### Memory Address Register
The Memory Address Register (MAR) in a 4-bit microprocessor is a register that holds the address of the memory location currently being accessed. The microprocessor uses the MAR to specify the address of the memory location it wants to read from or write to. The MAR is typically 4 bits wide, allowing it to address up to 16 memory locations in the microprocessor's memory space. The MAR is an important component for enabling the microprocessor to access and manipulate data stored in memory.

![MAR](https://user-images.githubusercontent.com/88718691/230791387-9ebe3963-d751-4963-9a5c-fcb52536f769.png)

###  B-register
The B-register in a 4-bit microprocessor is a register that holds a temporary data value used in arithmetic and logic operations. It can hold up to 4 bits of data and can be used to store data from memory, data entered by a user, or the results of previous calculations. The B-register is an important component for performing mathematical operations in a 4-bit microprocessor and is typically used in conjunction with the microprocessor's arithmetic logic unit (ALU).

### Accumulator
The accumulator in a 4-bit microprocessor is a register that holds the result of arithmetic and logical operations performed by the microprocessor. It can hold up to 4 bits of data and is used to store the intermediate results of calculations as well as the final result. The accumulator is a crucial component for performing mathematical and logical operations in a 4-bit microprocessor and is typically used in conjunction with the microprocessor's arithmetic logic unit (ALU).

![ACCU](https://user-images.githubusercontent.com/88718691/230791396-7ac47a75-c3f2-4e54-bffe-e1a967429003.png)

### Arithmetic Logic Unit
The Arithmetic Logic Unit (ALU) in a 4-bit microprocessor is a digital circuit that performs arithmetic and logic operations on binary data. It can perform operations such as addition, subtraction, logical AND, logical OR, and others. The ALU takes input from the microprocessor's registers, performs the requested operation, and outputs the result to the appropriate register, such as the accumulator or B-register. The ALU is an essential component for performing mathematical and logical operations in a 4-bit microprocessor.


![ALU](https://user-images.githubusercontent.com/88718691/230791383-d07194bc-e9fa-46b1-88c6-29523c857555.png)

### Output Register
The output register in a 4-bit microprocessor is a register that holds the output data from the microprocessor. It is typically used to temporarily store data that will be sent to an output device, such as a display or printer. The output register can hold up to 4 bits of data and is loaded with data from the accumulator or other registers before being sent to the output device. The output register is an important component for controlling the flow of data between the microprocessor and external devices.

![OUTPUT REGISTER](https://user-images.githubusercontent.com/88718691/230791340-a1549f02-38b9-4ce7-a622-996cde490939.png)


