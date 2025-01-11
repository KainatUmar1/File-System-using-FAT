# Custom File System Implementation using FAT

This repository contains my implementation of a **Custom File System** based on the **File Allocation Table (FAT)**, written entirely in C. This project was developed, providing hands-on experience with file system design and management.

## 📜 Project Overview

The project simulates a real-world file system with basic and advanced file management operations. A console interface is provided to interact with the file system, allowing users to create, manage, and manipulate files and directories.

## ✨ Features

### Core Functionality
1. **File Operations**:
   - Create a new file
   - Delete a file
   - Read an existing file
   - Write data to a file
   - Truncate a file

2. **Directory Operations**:
   - Create a new directory
   - Delete an existing directory
   - List all files and directories

3. **Partition Operations**:
   - Create and format the file system partition

4. **Low-Level Operations**:
   - Block-based read (`ReadBlock`)
   - Block-based write (`WriteBlock`)

### Additional Features
- Directory management and a FAT table for file organization
- Console-based interface for easy interaction
- Block-based read and write operations for efficient data handling

## ⚙️ System Settings
- **Directory Size**: 128 entries
- **Maximum File Name Size**: 64 bytes
- **Maximum File Size**: 128 blocks
- **Block Size**: 1 KB (1024 bytes)
- **Total Disk Size**: 64 MB

## 🚀 Getting Started

### Prerequisites
- A C compiler (e.g., GCC)
- Basic knowledge of file systems and operating systems concepts

### Instructions
1. Clone this repository.
2. Compile the source code:
   ```bash
   gcc -o file_system file_system.c
   ```
3. Run the file system:
   ```bash
   ./file_system
   ```
4. Interact with the file system through the console interface.

## 📖 Documentation
The entire implementation is contained in a single C file (`file_system.c`). Comprehensive documentation, including design considerations, challenges faced, and system details, is provided in this Readme file.

## 🏆 Key Learnings
- Hands-on experience with file system design
- Understanding file allocation techniques (FAT and indexed file systems)
- Efficient storage and retrieval using block-based operations
- Addressing challenges in directory and FAT table management

## 🤝 Contribution
Feel free to fork this repository and contribute! Suggestions, bug reports, and feature requests are welcome.

## Author
- **Kainat Umar** - *Developer of this `Custom FAT File System` using principles of Operating Systems.*
