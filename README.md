# Base x64 Linux Assembly

A starter project for building and running x64 architecture assembly language projects on Linux.

## Software Installation

This starter project uses the `yasm` assembler, the `gcc` compiler/linker, and the `make` build tool.  Even though it is not required to use this project, it is also recommended that you install `gdb`, which is a text-based debugger.

These tools can be installed with the following command:

`sudo apt install yasm build-essential gdb`

## Building the Program

The following command runs the assembler and links the resulting object code:

`make`

## Running the Program

The following command runs the assembler and links the resulting object code:

`./main.out`

## Cleaning Up

The following command deletes the binary files generated during the build process:

`make clean`
