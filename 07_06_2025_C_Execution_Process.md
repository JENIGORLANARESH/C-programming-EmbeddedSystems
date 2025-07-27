##  Write a C-program

    $vi sample.c

## Compilation

            compiler(gcc)               <br>
    C-Statements    ->  Instructions    
        |                   |
    sample.c----------> executable file
                            |
                            a.out
                        (assembly output)

* CPU only understands instructions

### gcc
*   g       ->  GNU (Organization which develops open source)
*   c       ->  C
*   c       ->  Compiler

### $gcc sample.c   -->     Exectable file( a.out )

## How to remove a file
```
    $rm filename
    $rm a.out
```

### How to get documentation for rm command
```
    $man rm
```

## Exection / Running a program

### $./a.out
*   a.out   -> executable file name
*   Program exection starts from main() function
*   ./      -> mentions that executable file is present in the current working directory

### There are two point views

1) Program point of view
    - Program exection starts from main()
    - Every program should have 1 function named main
    - main() function -> Entry point of program

2) System/Hardware point of view