# C Text Editor

Welcome to the C Text Editor! This is a minimal yet powerful text editor built in C, inspired by [antirez's kilo](https://github.com/antirez/kilo), with some modifications. It is a single-file program (~1000 lines of C) with minimal dependencies, featuring essential text-editing capabilities, syntax highlighting, and a search function.

## Features

- Basic text editing (insert, delete, and navigate text)
- Syntax highlighting for various programming languages
- Search functionality to find and navigate text quickly
- Minimal dependencies – runs in the terminal
- Simple, lightweight, and fast

## Getting Started

### Prerequisites

To compile and run the text editor, you'll need:

- A C compiler (e.g., `gcc`)
- A Unix-like environment (Linux, macOS, or Windows with WSL)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/eastona01/text-editor-in-c.git
   cd text-editor-in-c
    ```
2. Compile the program:
  ```sh
  gcc -o kilo kilo.c -Wall -Wextra -pedantic -std=c11
  ```
3. Run the editor:
  ```sh
  ./kilo filename.txt
  ```

### How It Works
This project was built step-by-step in 184 incremental changes, each carefully designed to introduce new functionality. You can follow along with the development process by reading the tutorial or exploring the commit history.

### Usage
- Open a file:
  ```sh
  ./kilo filename.txt
  ```
- Navigation: Use arrow keys or mouse to move the cursor.
- Editing: Type to insert characters, Backspace to delete.
- Search: Press Ctrl-F, type a search term, and press Enter.
- Save file: Press Ctrl-S to save changes.
- Quit editor: Press Ctrl-Q.

### Learning from the Code
If you want to learn how text editors work under the hood, this project serves as an excellent introduction. By following the 184-step guide, you’ll build the editor from scratch, learning about:

- Terminal input and output handling
- File I/O in C
- Syntax highlighting logic
- Efficient screen rendering techniques

### Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the editor.

### License
This project is licensed under the MIT License – feel free to use and modify it.

### Acknowledgments
Inspired by [kilo](https://antirez.com/news/108) by antirez
Based on a step-by-step [tutorial](https://viewsourcecode.org/snaptoken/kilo/index.html) to help understand text editor internals
