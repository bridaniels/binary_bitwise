# **Binary Numbers, Bits, and Bitwise Operators**

# **Binary Numbers**
---
- **8** Bits in a Byte 
- Bits Either **0** or **1**
- Bytes can be interpreted as: 
    - Binary Octal
    - Binary Hexadecimal *(16 Digits)*
    - Binary *(2 Digits)*

> **Number Base** = Number of Digits in a System of Counting 
>   - Base 10: 0,1,2,3,4,5,6,7,8,9
>   - Base 2 (Binary): 0,1

### In Binary Every Position Increases By A Multiple Of **Two**
| Place Value | 16 | 8 | 4 | 2 | 1 | Value |
|:------------|:--:|:-:|:-:|:-:|:-:|:------|
| Binary Number |  |  | 1 | 0 | 1 |  |
|  |  |  | 4 | +0 | +1 | = 5 |
| Binary Number | 1 | 0 | 1 | 0 | 1 |  |
|  | 16 | +0 | +4 | +0 | +1 | = 21 |

### Python Binary Notation: Prefix `0b`



# **Bytes: Character Encoding**
---
- Python Object: `bytes()` immutable, and `bytearray()` modifiable 
- assign values to bytes or sets of bytes 
- map binary numbers to characters 
- **UTF-8** used most widely today 
- **ASCII** = python default and oldest 
- `bytestring` = string of bytes -> `b'\x01\x02\x03\x04\x05'`


# **Bitwise Operations**
---