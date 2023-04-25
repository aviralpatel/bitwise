
# Bitwise operators in C

Bitwise operators in C are used to manipulate individual bits of data. These operators are used when you need to perform low-level bit manipulation or optimize memory usage.

## Bitwise AND

The bitwise AND operator (&) performs a logical AND operation between the corresponding bits of two operands. The result is 1 only if both bits are 1, otherwise the result is 0.

```
unsigned int a = 5;    
unsigned int b = 9;    
unsigned int c = a & b; 
```

## Bitwise OR

The bitwise OR operator (|) performs a logical OR operation between the corresponding bits of two operands. The result is 1 if at least one bit is 1, otherwise the result is 0.

```
unsigned int a = 5;    
unsigned int b = 9;    
unsigned int c = a | b;
```
## Bitwise XOR

The bitwise XOR operator (^) performs a logical XOR operation between the corresponding bits of two operands. The result is 1 if the bits are different, otherwise the result is 0.

```
unsigned int a = 5;    
unsigned int b = 9;    
unsigned int c = a ^ b;
```
