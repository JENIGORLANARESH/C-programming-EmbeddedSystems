# Bitwise Operator

* To manipulate individual bits of a data items we use bitwise operator
* Bitwise operators cannot be used on float types

####    &   Bitwise AND
####    |   Bitwise OR
####    ~   Bitwise NOT / Negation / 1's Complement
####    <<  Left Shift
####    >>  Right Shift
####    ^   Bitwise XOR

### Example
```
    int a = 5;   // Binary: 0101
    int b = 3;   // Binary: 0011

    a & b  → 1   // 0001
    a | b  → 7   // 0111
    a ^ b  → 6   // 0110
    ~a     → -6  // In 2's complement: 1010 (for 4-bit example)
    a << 1 → 10  // 1010
    a >> 1 → 2   // 0010
```
