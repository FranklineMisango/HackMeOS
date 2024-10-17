# HackMeOs

## Overview

This project aims to explore and experiment with the LC-3 architecture by creating and executing C programs that can be loaded and run on an LC-3 simulator. The end goal is to develop nanochess games and other scripts that can run directly on the LC-3 architecture.

## Objectives

1. **Understand the LC-3 Architecture**: Gain a deep understanding of the LC-3 architecture and how it executes instructions.
2. **Develop C Programs**: Write and test C programs that can be loaded and executed on the LC-3 simulator.
3. **Create Nanochess Games**: Develop simple chess games that can run within the constraints of the LC-3 architecture.
4. **Experiment with Other Scripts**: Explore other potential scripts and applications that can be executed on the LC-3 simulator.

## Project Structure

- `src/`: Contains all the C source code files.
- `docs/`: Documentation and resources related to LC-3 architecture.
- `tools/`: Utilities and scripts for compiling and testing the LC-3 code.
- `games/`: Nanochess games and other scripts developed for the LC-3 architecture.

## Prerequisites

- **Compiler**: GCC or any other C compiler that supports the LC-3 architecture.
- **Simulator**: An LC-3 simulator for testing the compiled code.
- **Debugger**: For inspecting and debugging binary files.

## Getting Started

1. **Set Up Environment**:
    - Install GCC: `sudo apt-get install gcc`
    - Install an LC-3 simulator.

2. **Compile the Code**:
    - Navigate to the `src/` directory.
    - Compile the main C code: `gcc -o main main.c`

3. **Test the Code**:
    - Use the LC-3 simulator to test the compiled code: `lc3sim main.obj`

## Development Workflow

1. **Write C Code**: Develop your C programs in the `src/` directory.
2. **Compile**: Use GCC to compile the code into an object file.
3. **Test**: Use an LC-3 simulator to test the compiled code.
4. **Debug**: Use a debugger to inspect and debug the binary files.

## Resources

- [LC-3 Documentation](docs/lc3.md)
- [LC-3 Instruction Set](docs/lc3_instruction_set.md)
- [C Programming Tutorials](docs/c_programming_tutorials.md)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.