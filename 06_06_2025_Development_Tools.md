# Development Tools

## Common Development Tools
- *Arduino IDE*
- *Keil IDE*

### These IDEs include:
- Text Editor
- Compiler
- Debugger
- Linkers/Loaders

---

## Program Development Process

1. Writing Code:
   - C programs are written using *text editor tools*.

2. Compilation:
   - *C statements ➝ Instructions*
   - Hardware is capable of processing and executing *instructions only*.

3. Translation Process:
   - C statements ➝ *Assembly code* ➝ Machine instructions
   - Converts high-level language (human understandable) into low-level machine language (machine understandable).

---

## Language Translation Flow

* C - statements  -> Assembly code  -> Instructions.

- *High-Level Language* ➝ *Low-Level Language*
- *Human understandable language* ➝ *Machine understandable language*

---

## Instructions Structure

* Instructions are made of:
#### Opcodes: Operational codes (e.g., ADD-78, SUB-70)
#### Operands: Address of memory locations in RAM

###  Opcode:
- A *unique code* that specifies the operation to be performed.

---

## Summary
- Development tools like Arduino IDE and Keil IDE help write, compile, debug, and upload code to embedded hardware.
- Compilation converts human-readable code into machine-executable instructions through a multi-step translation process.



### Basic Units of Memory

### Bits and Bytes
- Each bit → 0 or 1
- 8 bits → 1 Byte
- 16 bits → 2 Bytes
- 32 bits → 4 Bytes
- 64 bits → 8 Bytes

## RAM
- RAM is divided into *bytes*.
- Each byte has a *unique address*.
- Addresses are always represented in *hexadecimal form*.

---

# Errors in Programming

| Error Type       | Description                                | Tools           |
|------------------|--------------------------------------------|-----------------|
| *Compile-Time* | Errors while writing code (syntax, etc.)   | *Compiler*    |
| *Run-Time*     | Errors during program execution            | *Debugger*    |

-  *Compiler* helps find and resolve *compile-time errors*.
-  *Debugger* is used to find *run-time errors*.

---

# Loaders

- Tools like *Keil IDE* or Windows-based loaders help load compiled code to hardware.

### Process:
1. Write program (sample.c)
2. Compiler converts it to *instructions* (binary/hex/executable)
3. Loader sends the executable to the *target board* (microcontroller-based hardware).

### Connection Methods:
- Serial cable
- USB cable
- LAN cable

---

# Linux Environment Development Tools

## OS Used:
- *Ubuntu OS*

## Text Editors:
- *vi* — Basic text editor
- *vim* — Vi Improved (Visual Interface Improved)

## Command-Line Interface (CLI) Tools:
- Linux primarily uses *terminal/command line interface* for development.

### Terminal Behavior:
- Once opened, the terminal shows a *blinking cursor* called a *command prompt*.

### Common Terminal Commands:
- To open an existing file:



## Development Tools in Linux:
| Function    | Tool              |
|--------------|-------------------|
| *Compiler* | gcc (GNU C Compiler) |
| *Debugger* | gdb (GNU Debugger)   |
| *Loader*   | ldd (open an existing file) |

---

# Summary of Linux Environment
- Terminal is *pre-installed* in every Linux OS.
- Commands are used to run applications or tools.
- Terminal helps edit, compile, debug, and load code efficiently.

### printf()
* C standard input/output library function

### ls command
* To list files in a directory
* White  -  normal files
* Blue   -  Directories/folders
* Green  -  Executable files

### Assembly code files
*  .s extension

## File Permissions (file info)

1) File permissions (read / write / execute)
2) Username / Group name
3) Size of file
4) Date of creation (time startup)
5) Name of the file

## Flags/Options
   -  additional information is called flags or options
1) -a
2) -l
3) -p

* Example : $ls -l

## What are all the flags and options I can use along ls ? 
Ans: Documentaion for ls command / manual paper / help   <br>
      $man ls     ->    gives ducumentations <br>
      $ls --help  
