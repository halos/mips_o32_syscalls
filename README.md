Ghidra script for MIPS o32 executables

This script detects the syscall number and adds a PreComment to the syscall instruction and, if the function has not been renamed (it starts with "FUN_") it will be renamed with the syscal name.