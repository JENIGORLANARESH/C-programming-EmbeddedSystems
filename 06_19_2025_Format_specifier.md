# Format Specifier

Format specifiers, also known as format codes or format strings, are placeholders used in input and output functions to represent data types. They instruct the compiler on how to interpret and display data when using functions like printf() and scanf().

* Combination of percentile & conversion specification character.
*   % + conversion specification character
* Example : 
    -   %d , %i
    -   %x , %X
    -   %s
    -   %c
    -   %f
    -   %e , %E
    -   %g , %G
    -   %o
    -   %u
    -   %p
    -   %   - print a % sign

* printf() & scanf() funtions uses this format specifiers to specify size & data type.

## %c

```
        char ch = 'A';
        printf( "%c" , ch );        //output : A

        ch -> binary data -> ASCII value(65) -> ASCII character (A)

        printf( "%d" , ch );        //output : 65

        ch -> binary data -> ASCII value -> 65
```

* We can store integer value in a character variable.
```
        char ch = 65;
```

#### NOTE : We can only store only a specific range of values

```
        char ch = '#';
        printf( "%c" , ch );    //output : #
```

### Example : 

```
        char ch = 8;          // * ch is stored as Binary Data in Memory
        printf( "%c" , ch);       //output : "Wont see output"
        printf( "%d" , ch);       //output : 8
```

#### Note : ASCII values 0 -> 32 are NON PRINTABLE

### Example :

```
        char ch = '8';      // * ch is stored as Binary Data in Memory
        printf( "%c" , ch);     //output : 8 (numeric char)
        printf( "%d" , ch);     //output : 56 (ascii value of char '8')
```

### Example :

``` 
        char ch = 0;
        printf( "%c" , ch );     //output : No ouput display
        printf( "%d" , ch );    // output : 0 (ascii value)
```


<img width="686" height="519" alt="ascii_zero" src="https://github.com/user-attachments/assets/6e40e15a-ee18-4c80-b701-695eaa9f2ae5" />


### Example : 

```
        char ch = '0';      // numeric character or ascii character
        printf( "%c" , ch );    //output : 0 (ascii character)
        printf( "%d" , ch );    //output : 48 (ascii value)
```


<img width="684" height="253" alt="char_0" src="https://github.com/user-attachments/assets/63360b48-65ed-44b0-81e1-0649f2d6a19e" />


## ASCII values of Numerics

* Numerics are 48 to 57
    - 0 -> 48
    - 1 -> 49
    - 2 -> 50
    - 3 -> 51
    - 4 -> 52
    - 5 -> 53
    - 6 -> 54
    - 7 -> 55
    - 8 -> 56
    - 9 -> 57

