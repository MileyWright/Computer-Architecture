# Computer Architecture: Basics, Number Bases

At the end of this module, you should be able to:
- describe the functional components of a CPU
- convert between and understand decimal, binary, and hexadecimal

-----------

# Number Bases
- Binary 
- Hexidecimal

Q: Why do we want different number bases as we program? Why should we have more than say, 'decimal -- why is it useful? & How many number bases do we commonly use in computer programming?
A: To store larger numbers in less place (Hexadecima!) - most common are binary, decimal, hexadecimal, octal, base8, base64. We are used to decimal, but computers use binary deep down, and 10 is not a power of 2. Binary works great for booleans (true & false). Base2 for computers works great with binary. 

![conversion methods](https://circuitglobe.com/wp-content/uploads/2016/09/hexadecimal-to-binary-conversion-examples-3.jpg)

## Binary
- 0s & 1s


## Hexadecimal
- 16, 0-9, A-F
0x = base16 = hexadecimal

```
Ex #1) 54 --> hex
54 / 16 = 3.??
54-48 = 6
0x36
```
```
Ex #2) 0xE3 --> decimal
E = 14
x = 16
(14 * 16) + 3 = 227
```
```
Ex #3) 0b1101010 --> decimal
2 + 8 + 64 + 128 = 74 + 128 = 198 + 4 = 202
```
```
Ex #4) 0b10101100 ---> hex
# TRICK
[101011000] = 8 bits = 1 byte 
1 byte = 2 nibbles
0b 1010 1100 ---> hex
0xAC = hex
0xAc --> decimal
(10 * 16) + 12 = 160 + 12 = 172
decimal --> hex --> binary
```
```
Ex #5) 0b11111111 ---> decimal
1111 1111
15 + 15
F + F
0xFF
```