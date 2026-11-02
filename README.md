# virtual-file-system-cpp
Virtual File System Implementation Using C++ - MITS Gwalior Macro Project I
# Virtual File System Implementation Using C++

## Project Overview
This project implements a simple Virtual File System (VFS) using C++. It simulates disk storage in memory and provides basic file and directory management operations.

## Features
- Virtual disk with 20 storage blocks
- File creation using `touch`
- Writing data using `write`
- Reading file contents using `read`
- Creating directories using `mkdir`
- Directory navigation using `cd`
- Listing files and directories using `ls`
- Interactive command-line interface

## Technologies Used
- C++
- Standard Template Library (STL)
- Vectors, Maps, and Strings
- Data Structures and Operating System Concepts

## How to Run
1. Download the C++ source file.
2. Open it in a C++ compiler or IDE.
3. Compile the program using a C++17-compatible compiler.
4. Run the executable and enter commands in the terminal.

## Example Commands
```text
mkdir documents
cd documents
touch notes.txt
write notes.txt "Hello Virtual File System"
read notes.txt
ls
cd ..
exit
```

## Project Purpose
The purpose of this project is to understand file system architecture, inode metadata, block allocation, directory structures, and basic file operations.
