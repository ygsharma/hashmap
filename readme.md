# Hashmap Implementation in C

## Overview

This repository contains an implementation of a hashmap in C. A hashmap (also known as a hash table) is a data structure that implements an associative array, a structure that can map keys to values. This implementation includes basic operations such as insertion, deletion, and searching for values based on their keys.

## Project Structure

```
├── a.exe # Executable file
├── hashmap.c # Implementation of the hashmap
├── hashmap.h # Header file for the hashmap
├── main.c # Main program to test the hashmap
├── run.sh # Shell script to compile and run the program
```


## Getting Started

### Prerequisites

- GCC (GNU Compiler Collection) to compile the C programs
- Shell environment to run the shell script (`run.sh`)

### Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/ygsharma/hashmap.git
    cd hashmap
    ```

2. **Compile the Code**
    You can compile the code manually using GCC or use the provided shell script.

    **Manual Compilation**
    ```bash
    gcc -o hashmap main.c hashmap.c
    ```

    **Using the Shell Script**
    ```bash
    ./run.sh
    ```

3. **Run the Executable**
    ```bash
    ./hashmap
    ```

## Usage

The `main.c` file contains sample code to demonstrate the usage of the hashmap. You can modify this file to test different functionalities and operations of the hashmap.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to fork the repository, make your changes, and submit a pull request.
