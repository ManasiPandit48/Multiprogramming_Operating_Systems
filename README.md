# Multiprogramming Operating System

### Description
This project is developed in multiple phases to implement core operating system concepts. Each phase builds on the previous one, introducing new functionalities and optimizations to simulate certain OS processes.

### Folder Structure
- **Source Code**: Includes `os_phase2_final.c` for Phase 2 and `Phase1_new.cpp` for Phase 1.
- **Executables**: Compiled binaries (`.exe` and `.o` files) for testing the implementation.
- **Input and Output Files**: Pre-defined input (`input1.txt`, `i2.txt`) and output files (`output1.txt`, `o2.txt`) for validating program results.
- **Documentation**: `CP_PPT_G14.pdf` provides an overview and additional insights into the project.

### Requirements
- C/C++ Compiler (e.g., GCC for Linux or MinGW for Windows)
- (Optional) IDE for editing source code (e.g., Visual Studio Code)

### Installation and Execution

1. **Compile the Code**:
   ```bash
   gcc -o os_phase2_final os_phase2_final.c   # For Phase 2
   g++ -o Phase1_new Phase1_new.cpp           # For Phase 1
   ```

2. **Run the Executable**:
   - To run the executable with the input files:
     ```bash
     ./os_phase2_final < input1.txt > output1.txt
     ./Phase1_new < i2.txt > o2.txt
     ```

### Usage
Run the appropriate executable file for each phase to simulate the functionality being implemented.

### License
This project is intended for educational purposes.
