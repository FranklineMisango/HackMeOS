# HackMeOs

## Overview

This project aims to explore and experiment with the LC-3 architecture by creating and executing a virtual C OS that can be emulate the LC-3 architecture. 

## Objectives

1. **Understand the LC-3 Architecture**: Gain a deep understanding of the LC-3 architecture and how it executes instructions.
2. **Develop C Programs**: Write and test C programs that can be loaded and executed on the LC-3 simulator.
3. **Create Nanochess Games**: Develop simple chess games that can run within the constraints of the LC-3 architecture.
4. **Experiment with Other Scripts**: Explore other potential scripts and applications that can be executed on the LC-3 simulator.

## Project Structure
-  The main file is the main.c 
- `lc3tools/`: Contains all the assembly code compiled to obj and in .asm format
- `docs/`: Documentation and resources related to LC-3 architecture.

## Prerequisites

- **Compiler**: GCC or any other C compiler that supports the LC-3 architecture.

1. **Set Up Environment**:
    - Install GCC: `sudo apt-get install gcc`

2. **Compile the Code**:
    - Compile the main C code: `gcc -o main main.c`

3. **Test the Code**:
    - : `./main lc3tools/simple.obj`

## Resources

- [LC-3 Documentation](docs/lc3.md)
- [LC-3 Instruction Set](docs/lc3_instruction_set.md)
- [C Programming Tutorials](docs/c_programming_tutorials.md)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.