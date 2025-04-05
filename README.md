# Lexical Analyzer in C++

This is a simple **Lexical Analyzer** implemented in **C++**. The program reads an input file (`front.in`), analyzes the content, and outputs the lexemes along with their corresponding token codes.

## 📋 Features

- Recognizes:
  - Identifiers (e.g., `x`, `total`, `sum1`)
  - Integer literals (e.g., `123`, `42`)
  - Arithmetic operators (`+`, `-`, `*`, `/`)
  - Assignment operator (`=`)
  - Parentheses (`(` and `)`)
- Ignores whitespace
- Outputs a token and its lexeme for each recognized element

## 🧠 Token Codes

| Token        | Code |
|--------------|------|
| Integer Literal (`INT_LIT`) | 10   |
| Identifier (`IDENT`)        | 11   |
| Assignment Operator (`=`)   | 20   |
| Addition Operator (`+`)     | 21   |
| Subtraction Operator (`-`)  | 22   |
| Multiplication Operator (`*`)| 23  |
| Division Operator (`/`)     | 24   |
| Left Parenthesis (`(`)      | 25   |
| Right Parenthesis (`)`)     | 26   |
| End of File (`EOF`)         | -1   |

## 📁 File Structure

- `main.cpp` — The main source code for the lexical analyzer.
- `front.in` — The input file containing source code to be analyzed.

## 🛠️ How to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/lexical-analyzer-cpp.git
    cd lexical-analyzer-cpp
    ```

2. **Add an input file** named `front.in` in the same directory. Example:
    ```
    sum = 25 + 42 / total
    ```

3. **Compile the program**:
    ```bash
    g++ main.cpp -o lexer
    ```

4. **Run the executable**:
    ```bash
    ./lexer
    ```



## 🤝 Contributing

Feel free to fork this project and submit a pull request if you'd like to add new features like:
- Support for floating-point numbers
- Multi-character operators (`==`, `!=`, etc.)
- Comments handling
- Error reporting

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy Lexing! 🚀
