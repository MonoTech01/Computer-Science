# Computer Data Storage

## What is Computer Memory?

- **Definition**: Any type of electronic storage.
- **Importance**: Without memory, a computer cannot function; it is crucial from startup to shutdown.

## Types of Memory

1. **Primary Memory**: 
   - **Definition**: Main storage for quick access by the CPU.
   - **Types**: Includes RAM and ROM.

2. **Secondary Memory**:
   - **Definition**: Additional storage for data and programs.
   - **Examples**: Hard drives, SSDs (Solid State Drives).

## Key Memory Components

### 1. Random Access Memory (RAM)

- **Definition**: Volatile memory used during active processes.
- **Characteristics**: 
  - Data is lost when the computer is turned off.
  - Shared among running programs.
  - Measured in gigabytes (GB).
  - Types: DDR3, DDR4 (ensure compatibility with the motherboard).
- **Analogy**: Like a gardener who forgets their work each day but resumes it when instructed.

### 2. Read-Only Memory (ROM)

- **Definition**: Non-volatile, permanent memory.
- **Function**: Stores startup instructions, such as BIOS or UEFI.
- **Characteristics**: 
  - Data remains after the computer is turned off.
  - Typically 4 to 8 megabytes (MB).
- **Analogy**: Permanent memories like life events.

### 3. Cache Memory

- **Definition**: Small, volatile memory for frequently accessed data.
- **Types**:
  - **Level 1 Cache**: Very small, fastest access, directly used by the CPU.
  - **Level 2 Cache**: Larger, connected to the CPU, used most frequently (~95% of the time).

### 4. Virtual Memory

- **Definition**: Extends RAM by using a portion of the hard drive.
- **Function**: Allows large programs to run and supports multitasking by creating "swap files".
- **Consideration**: 
  - Helps manage multiple applications like spreadsheets, browsers, and editors.
  - Excessive use can slow down system performance due to increased disk swapping.

## Memory's Place in a Computer

### Start-up Process

1. **Power On**: Computer accesses ROM.
2. **BIOS/UEFI**: Runs startup routines and tests memory.
3. **Load Operating System**: OS is loaded into RAM, giving CPU quick access.

### Running Applications

- **Example**: Running Microsoft Word:
  - Application loaded into RAM for active use.
  - Files accessed from storage into RAM.
  - Upon saving and closing, data moves from RAM back to storage.

## Memory and Storage Hierarchy

- **Diagram Overview**: Displays all inputs/outputs and processing units.
  - **CPU**: Central Processing Unit, brain of the computer.
  - **Primary Memory**: RAM and ROM.
  - **Secondary Memory**: Hard drives and other storage devices.
  - **Cache Memory**: Provides quick access to frequently used data.
  - **Virtual Memory**: Extends available memory using hard drive space.

## Memory Usage in Computers

### Hierarchical Memory Management

1. **Primary Memory**:
   - Quick access and processing by the CPU.
2. **Secondary Memory**:
   - Long-term data storage.
3. **Cache Memory**:
   - Fast access for repetitive tasks.
4. **Virtual Memory**:
   - Supports large applications and multitasking by extending RAM capabilities.
