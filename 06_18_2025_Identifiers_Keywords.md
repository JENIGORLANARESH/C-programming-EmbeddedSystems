# IDENTIFIER

- The name given to elements in C.
- It is used to identify : Variables, Arrays, Funtions, Structures, Unions, etc.
- Names given to Memory Locations.
  <br>

- Example :

```
            int val;
  Data type<-|   |-----> Variable
            val = 25;
```

- System point of view :
  - Creating 4 bytes of memory
  - 4 bytes of memory has a name "val"
  - 25 is stored in 4 bytes of memory named as val.

## Rules for naming an Identifier

1. Identifier can contain alphabets, numerics, only one special character( \_ )

   - Example :
     - int val_20; //Correct
     - int val.20; //Incorrect

2. Identifier names should start with alphabets and underscore( \_ )

   - Cannot start with numerics
   - Example :
     - int val; // correct
     - int \_temp; // correct
     - int 2_temp; // Incorrect

3. Identifier should NOT use KEYWORDS.

   - Total KEYWORDS = 32

4. C is Case Sensitive

   - Uppercase and Lowercase are treated as differently
   - They have different ASCII values
   - We cannot have two variables with same name within same funtion.
   - Example :
     ```
         int main(){
             int val;
             int val;  -> compilation error
             int VAL;  -> different from first variable because case change
         }
     ```
   - val , Val , VAL are treated as different variables.

5. Identifier can be of any length, But compiler recognizes only first 31 characters.

   - 32-bit compiler
     - recognizes first 31 characters
     - gcc(Linux)
     - arm-linux-gcc -> Cross compiler
   - 16-bit compiler
     - recognizes first 8 characters
     - Turbo-C (Windows)

6. White spaces or blank spaces are not allowed within identifier names.
   - The same rule apply for naming a variable, Arrays, Structures, Union

<br>
<br>
<br>

# Keywords

- "Reserved Word" that has a special meaning to the compiler.
- Pre defined words.
- All keywords are lowercase
- Total 32 keywords in C
- Cannot be used as Identifiers, funtions, variables.
- Example :
  - int, float, if, else, while, return, for, void, break, continue, char, struct, typedef, const, static, switch, case, do, default, enum, extern, goto, long, register, short, signed, sizeof, union, unsigned, volatile, auto, double

## Data Types

- Data type is always associated with variable name

```
          int val;
          |     |
 predefined     userdefined
          |     |
    keyword     identifiers
          |     |
  datatypes     variables
```

## Premitive Data Types

- Basic data types / Built in data types
- char
- short
- int
- float
- long
- double

## Non premitive / Derived Datatypes / User defined data types

- Arrays
- Structures
- Unions

* By using basic data types we can create Arrays, Structures, Unions

* int val; -> variable declaration
* Before using any variable we have to declare the variable

# What does a data type specify?

- How many bytes the corresponding variable occupies.
- What type of data is stored in corresponding variable.
- Range of values that can be stored in corresponding variable.

#### char ch; -> 1 Byte

<img width="865" height="220" alt="image" src="https://github.com/user-attachments/assets/bcaf4225-b52a-48f9-b330-3cd41cd74739" />
<img width="432" height="170" alt="image" src="https://github.com/user-attachments/assets/44b8818e-6fce-4b76-b0ef-240defc7a5df" />
<img width="433" height="148" alt="image" src="https://github.com/user-attachments/assets/401b5032-4e9b-4d35-9dee-478eab192ade" />

<img width="751" height="281" alt="image" src="https://github.com/user-attachments/assets/a3f1a1a8-9fa8-443e-926c-283148a7d82b" />


#### short sval; -> 2 Bytes

#### int val; -> 4 Bytes

<img width="1368" height="827" alt="image" src="https://github.com/user-attachments/assets/ff33ba57-dad1-4900-8467-0b68177281e2" />


#### long lval; -> 8 Bytes

#### float fval; -> 4 Bytes

#### double dval; -> 8 Bytes

### integer values

- short
- int
- long

### float values

- long
- double
