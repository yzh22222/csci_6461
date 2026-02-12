# USER GUIDE

## Introduction
Welcome to the CSCI6461 Assembler project. This user guide provides an overview of how to utilize the assembler, including installation, usage, and troubleshooting.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yzh22222/csci_6461.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd csci_6461/CSCI6461_Assembler
   ```
3. **Compile the assembler**:
   ```bash
   make
   ```

## Usage
To assemble a file:
```bash
./assembler <source_file.asm> <output_file.obj>
```

### Parameters:
- `<source_file.asm>`: The source file written in the assembler language.
- `<output_file.obj>`: The output object file where assembled code will be written.

## Features
- Support for multiple assembly instructions.
- Option to include libraries.
- Automatic error detection during assembly process.

## Troubleshooting
- **Error: Unrecognized instruction**:
  Ensure that the instruction is valid. Refer to the instruction set documentation for valid commands.
- **Error: File not found**:
  Check the file path and ensure the file exists.

## Conclusion
For further assistance, please refer to the project's GitHub issues page or contact the project maintainers.

---

This user guide is effective as of 2026-02-12. 
