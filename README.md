# C64 Hardware Simulator for Windows

A Windows-oriented version of [c64-hw-simulator](https://github.com/antirez/c64-hw-simulator), the Commodore 64 hardware simulator created by [antirez](https://github.com/antirez).

The goal of this project is to make this unique hardware simulation tool accessible to Windows users, allowing them to explore the Commodore 64 motherboard, experiment with hardware faults, and better understand how the original machine works.


## Requirements

Requirements depend on the Windows build and distribution method.

- A Windows PC.
- A compatible Windows executable, if using a prebuilt release.
- The appropriate runtime libraries, if required by the selected build.

For source builds, consult the build instructions included with this repository.

## Installation

### Option 1: Prebuilt executable

If a Windows release is available:

1. Open the repository's **Releases** page.
2. Download the Windows package.
3. Extract the archive, if necessary.
4. Run the simulator executable.

If no Windows release is available, build the project from source using the instructions provided for the current version.

### Option 2: Build from source

The original project uses C and includes its graphics and user-interface dependencies in the `third_party/` directory.

The upstream build instructions target macOS and Linux with OpenGL. Windows-specific build instructions must match the toolchain and platform changes used in this repository.

Original project: https://github.com/antirez/c64-hw-simulator


## Original Project and Credits

This project is based on the work of [Salvatore Sanfilippo (antirez)](https://github.com/antirez), creator of the original C64 Hardware Simulator.

The upstream project builds on work by:

- **Andre Weissflog (floooh)** — Cycle-accurate chip cores and the `chips` project.
- **bwack** — KiCad Commodore 64 motherboard replica.
- **Mark Smith and Marko Mäkelä** — PLA logic equations.

Please consult the original repository for the complete acknowledgements and licensing information.

## License

Please refer to the original project's license and the licenses of its third-party components before redistributing or modifying the software.

The licensing terms for this Windows-specific repository and any platform-specific modifications should be documented here once verified.

## Links

- **Original project:** https://github.com/antirez/c64-hw-simulator
- **Author:** https://github.com/antirez

---

*This repository is intended to make Commodore 64 hardware simulation more accessible to Windows users while preserving the educational and diagnostic goals of the original project.*
