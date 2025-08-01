Dennis Ritchie - creator<br>
Bell Labs in early 1970<br>

#Basic Elements

1) Character set
2) Identifiers
3) Keywords
4) Data types
5) Constants
6) Variables
7) Expressions
8) Statements

* NOTE: main() is the entry point of program.

# Character Set

### Alphabets

* Uppercase & Lowercase
    - A, B, C, ....... , Z
    - a, b, c, ....... , z

* ASCII : Unique value of every character.
    - American Standard Code for Information Interchange
    - Ex : A -> 65  , a -> 97
* C is a CASE SENSITIVE language in which both uppercase & lowercase values are treated differently

### Numbers

* 0, 1, 2, .... , 9
* Numeric characters are also associated with ASCII values
    - 0 -> 48
    - 1 -> 49
    - 9 -> 57

### Special Symbols

* Ex : + , - , / , * , % , " , ! , ` , % , $ , # etc.

### Backlash characters (or) Escape Sequences

* '\' characters are escape sequences
* \ + alphabets
* \ + numerics

* Example : \n  \r  \b  \t  \a  \0

* They are not treated as two characters. 
* They are treated as SINGLE CHARACTER
* Most of the backslash characters are used in printf();
* \0  -> It is not used in printf();
* \0  -> It used for string termination.

### printf()
* C Standard Input/Output library function.
* Used to display output to screen.

### Funtion

#### Funtion -> Data Processing -> task

* Multiple inputs (arguments / parameter)
* Single output
* We can provide multiple inputs seperated by commas.
<br>
<br>
<br>

* \ Characters are used within printf() to change or alter cursor position.
* \ characters are NON PRINTABLE characters.
    - Example : printf("Hello\n");
    - Hello -> printable
    - \n -> Non printable
* \n -> Shift cursor to next line starting position

#### LINE FEED
* \n is represented using a different name LF, stands for "Line Feed"
* ASCII value :     LF -> 10
<br>

* We have 128 ASCII Characters.
* starting from 0 to 127
* For SPACE the ASCII value is 32.  SPACE -> 32
* ASCII for DEL -> 127

<br>
<br>

* Character set is divided into 2 groups

## Printable Characters
1) Alphabets
2) Numerics
3) Special Symbols

## Non printable characters
1) Black Slash Characters