# C-CALC CLI

<div align="center">
<img width="50" src="https://user-images.githubusercontent.com/25181517/192106070-46255bcf-65e6-4c6b-a296-bf8d0d8fb2a7.png" alt="C" title="C"/>
<p>c-calc</p>
</div>

Simple calculator application based on CLI which built on C

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/itsnotazis/c-calc
    ```

### How to Run

1. Makefile compilation:

   ```bash
   make
   ./bin/main
   ```

2. Manual compilation (use gcc):

   ```bash
   gcc -Iinclude src/main.c src/calc.c src/utils.c -o bin/main && ./bin/main
   ```

## Folder Structure

- `include/`: Header files
- `src/`: Source code files
- `bin/`: Compiled files (output binaries)
- `Makefile`: Build automation

---

### **Benefit using this structure**

1. **Organize**:

   - Source code, header, and build file result separated, make it easier for navigate project.

2. **Scalability**:

   - This structure make it easier for adding new feature, like additional source file, testing, or documentation.

3. **Easy to build**:

   - With `Makefile`, build process, clean up, and testing become automatically.

With this structure, the calculator application can developing furthermore easily.

## Features
There is some feature that i have included on this project:

1. Addition 
2. Subtraction
3. Multiplication
4. Division

## Author 
- [itsnotazis](https://github.com/itsnotazis) <itsnotazis@gmail.com>
- others...

## Final Touch

Thanks for using, contribute, even developing this simple calculator application. If this project help you, give it a star :D
