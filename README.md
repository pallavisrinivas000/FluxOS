# FluxOS

An operating system built from scratch as a learning project to understand operating system fundamentals.

## Overview

FluxOS is a custom operating system development project that aims to create a basic operating system from the ground up. This project serves as both a learning experience and a practical implementation of operating system concepts.

## Project Goals

- Implement a basic bootloader
- Create a minimal kernel
- Develop basic memory management
- Implement process scheduling
- Add basic device drivers
- Create a simple file system

## Prerequisites

To build and run FluxOS, you'll need:

- NASM (Netwide Assembler)
- GCC Cross-Compiler
- QEMU (for testing and emulation)
- Make
- (Add other tools as needed)

## Building from Source

1. Install the required dependencies
2. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FluxOS.git
   cd FluxOS
   ```
3. Build the project:
   ```bash
   make build
   ```
4. Run in QEMU:
   ```bash
   make run
   ```

## Project Structure

```
FluxOS/
├── src/
│   ├── boot/       # Bootloader code
│   ├── kernel/     # Kernel source
│   ├── drivers/    # Device drivers
│   └── lib/        # Common libraries
├── include/        # Header files
├── tools/         # Build tools and utilities
└── docs/          # Documentation
```

## Features (Planned/Implemented)

- [ ] Basic Bootloader
- [ ] Memory Management
- [ ] Process Scheduling
- [ ] Interrupt Handling
- [ ] Basic File System
- [ ] Device Drivers
- [ ] User Space Programs

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Learning Resources

- [OSDev Wiki](https://wiki.osdev.org/)
- [Writing an OS in Rust](https://os.phil-opp.com/)
- [Little OS Book](https://littleosbook.github.io/)
- [xv6 Documentation](https://pdos.csail.mit.edu/6.828/2019/xv6.html)


