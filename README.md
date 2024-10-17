# HackMeOs

## Overview

This project aims to explore and experiment with the Master Boot Record (MBR) by creating and executing assembly scripts that exploit the first 510 bytes of the boot sector before the operating system initializes. The end goal is to develop nanochess games and other scripts that can run directly from the boot sector.

## Objectives

1. **Understand the MBR**: Gain a deep understanding of the MBR structure and how it interacts with the BIOS during the boot process.
2. **Develop Assembly Scripts**: Write and test assembly scripts that can be loaded and executed from the MBR.
3. **Create Nanochess Games**: Develop simple chess games that can run within the constraints of the MBR.
4. **Experiment with Other Scripts**: Explore other potential scripts and applications that can be executed from the boot sector.

## Project Structure

- `src/`: Contains all the assembly source code files.
- `docs/`: Documentation and resources related to MBR and BIOS.
- `tools/`: Utilities and scripts for assembling and testing the MBR code.
- `games/`: Nanochess games and other scripts developed for the MBR.

## Prerequisites

- **Assembler**: NASM (Netwide Assembler) or any other assembler that supports x86 assembly.
- **Emulator**: QEMU or Bochs for testing the boot sector code.
- **Hex Editor**: For inspecting and modifying binary files.

## Getting Started

1. **Set Up Environment**:
    - Install NASM: `sudo apt-get install nasm`
    - Install QEMU: `sudo apt-get install qemu`

2. **Assemble the Code**:
    - Navigate to the `src/` directory.
    - Assemble the boot sector code: `nasm -f bin boot.asm -o boot.bin`

3. **Test the Boot Sector**:
    - Use QEMU to test the boot sector: `qemu-system-x86_64 -drive format=raw,file=boot.bin`

## Development Workflow

1. **Write Assembly Code**: Develop your assembly scripts in the `src/` directory.
2. **Assemble and Link**: Use NASM to assemble the code into a binary format.
3. **Test**: Use QEMU or Bochs to test the boot sector code.
4. **Debug**: Use a hex editor and debugging tools to inspect and debug the binary files.

## Resources

- [MBR Documentation](docs/mbr.md)
- [BIOS Interrupts](docs/bios_interrupts.md)
- [Assembly Language Tutorials](docs/assembly_tutorials.md)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.