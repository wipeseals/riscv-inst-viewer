# RISC-V Inst Viewer

[![Deploy static content to Pages](https://github.com/wipeseals/riscv-inst-viewer/actions/workflows/static.yml/badge.svg?branch=master)](https://github.com/wipeseals/riscv-inst-viewer/actions/workflows/static.yml)

A RISC-V instruction set visualization and analysis tool to support RISC-V development and debugging. Provides instruction listing and numerical decoding functionality to streamline processor development and assembly programming workflows.

🚀 **Demo Site**: <https://wipeseals.github.io/riscv-inst-viewer/>

## Features

- **Instruction Listing**: Comprehensive display of RISC-V extension instruction sets (RV32I/RV64I, M, A, F, D, C, Zicsr, etc.)
- **Instruction Decoding**: Reverse lookup and decoding of RISC-V instructions from 32-bit numerical values
- **Architecture Support**: Compatible with both RV32 and RV64 architectures
- **Format Visualization**: Visual display of instruction encoding formats (R-type, I-type, S-type, etc.)
- **Standalone Operation**: Executable as a single HTML file with no external dependencies
- **Responsive Design**: Compatible with both desktop and mobile environments
- **Dark Mode**: Light/dark theme switching support

## Usage

1. Open `index.html` in a web browser
2. Search for instruction names in the "Search Instructions" section, or enter hexadecimal values in the "32-bit Instruction Decoder"
3. View detailed instruction information and encoding

## RISC-V Specifications & Design Resources

- [RISC-V Instruction Set Manual](https://riscv.org/technical/specifications/) - Official specifications
- [RISC-V International](https://riscv.org/) - RISC-V organization
- [RISC-V Assembly Programmer's Manual](https://github.com/riscv-non-isa/riscv-asm-manual) - Assembly programming manual
- [RISC-V Green Card](https://www.cl.cam.ac.uk/teaching/1617/ECAD+Arch/files/docs/RISCVGreenCardv8-20151013.pdf) - Instruction set reference
- [RISC-V Opcodes](https://github.com/riscv/riscv-opcodes) - Instruction set definitions

## Supported Extensions

- **RV32I/RV64I**: Base integer instruction set
- **M**: Multiplication and division extension
- **A**: Atomic operations extension  
- **F**: Single-precision floating-point extension
- **D**: Double-precision floating-point extension
- **C**: Compressed instruction extension
- **Zicsr**: CSR operations extension
- **Zifencei**: Instruction fence extension

## Technical Specifications

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Browser Support**: Chrome, Firefox, Safari, Edge (modern browsers)

## Contributing

Pull requests and issue submissions are welcome! We look forward to proposals for adding new instruction sets and feature improvements.

## Installation

Simply open `index.html` in a web browser to use the tool.

## License

This project is released under the MIT License. See the `LICENSE` file for details.
