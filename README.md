# Game Boy Emulator
A Game Boy emulator written in C++20. I’m building this project to expand my knowledge! The emulator currently executes small programs through a command-line interface. Full games are not playable yet.

## Current features

- ROM loading and cartridge header inspection
- CPU registers and flags
- Memory bus with ROM & RAM access
- Register, memory, and immediate byte loads
- Arithmetic, logic, and 8-bit increment/decrement instructions
- Basic jumps, stack operations, and subroutine calls

## Build
CMake 3.28.3 or newer and a C++20 compiler

```sh
cmake -S . -B build
cmake --build build
```

## References
- [Game Boy Hardware Documentation](https://gbdev.io/pandocs/About.html)
- [CPU instruction behavior](https://rgbds.gbdev.io/docs/v1.0.4/gbz80.7)
