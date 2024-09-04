# Binary

## Introduction to Binary Information

- **Binary Definition**: 
  - 'Binary' means two possible values: 0 and 1.
  - All data in a computer system is in binary form, also referred to as machine language.

## Physical Storage of Binary Information

- **Transistors**: 
  - Microscopic switches in the CPU.
  - **Closed Switch**: Current flows, representing 1.
  - **Open Switch**: No current, representing 0.

- **Magnetic Properties**: 
  - Magnetic polarities represent binary 0s and 1s.

- **Optical Disks**: 
  - CDs and DVDs store binary information as pits and lands.

## Binary Notation

- **Bit**: 
  - Short for binary digit; can be 0 or 1.
  - **Multiple Bits**: Used to represent more values:
    - 2 bits = 4 values: 00, 01, 10, 11.
    - 3 bits = 8 values: 000, 001, 010, 011, 100, 101, 110, 111.
    - **General Formula**: 'n' bits represent $2^n$ values.

- **Example**: Representing decimal numbers 0 to 10 in binary:
  - Requires 4 bits (since 3 bits can only represent up to 8 values).

- **Modern Computers**:
  - Use 32-bit or 64-bit architecture.
  - **32-bit**: Represents $2^{32}$ values, up to 4,294,967,295 in decimal.

## Binary Coding Schemes

### Numbers and Text Representation

- **ASCII**:
  - American Standard Code for Information Interchange.
  - Originally 7-bit, representing 128 characters.
  - Expanded to 8-bit, 16-bit, or 32-bit for more characters.

- **Unicode**:
  - Supports over 110,000 characters for most of the world's languages.
  - Versions: UTF-8, UTF-16, UTF-32.
  - UTF-8 is nearly identical to ASCII.

### Example of ASCII Characters:

| Character | ASCII Code (7-bit) |
|-----------|--------------------|
| A         | 01000001           |
| B         | 01000010           |
| ...       | ...                |
| z         | 01111010           |

## Binary Representation of Other Data

- **Photographs**:
  - Pixels represent colors using combinations of three color values.
  - 8-bit color means each color value can range from 0 to 255.

- **Sound and Video**:
  - Digital formats represent sound waves and video frames as binary data.

## Bits and Bytes

- **Bit**:
  - Smallest unit of data, either 0 or 1.
- **Byte**:
  - Consists of 8 bits.
  - Historically, one byte used to store one character.

- **Units**:
  - Kilobyte (kB): $2^{10}$ bytes or 1024 bytes.
  - Megabyte (MB): $2^{20}$ bytes.
  - Gigabyte (GB): $2^{30}$ bytes.
  - Terabyte (TB): $2^{40}$ bytes.
