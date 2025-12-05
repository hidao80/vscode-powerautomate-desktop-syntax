# Power Automate Desktop Syntax Highlighting

This Visual Studio Code extension provides syntax highlighting for [Power Automate Desktop](https://flow.microsoft.com/) blocks.

## Features

- Syntax highlighting for Power Automate Desktop scripts
- Supports keywords, functions, variables, strings, numbers, booleans, operators, comments, and embedded JSON blocks
- Recognizes `.powerautomate` file extension

## Installation

1. Download or clone this repository.
2. Open the folder in Visual Studio Code.
3. Press `F5` to launch an Extension Development Host with the syntax highlighting enabled.

## Usage

- Open any `.powerautomate` file in VS Code to see syntax highlighting.
- The extension automatically applies highlighting based on the defined grammar.

## Supported Syntax

- **Keywords:** `LOOP`, `IF`, `THEN`, `END`, `EXIT`, `WAIT`
- **Functions:** Any alphanumeric or dot-prefixed identifier at the start of a line
- **Variables:** Alphanumeric identifiers followed by a colon (e.g., `varName:`)
- **Strings:** Single, double, and triple quoted strings
- **Numbers:** Integers and decimals
- **Booleans:** `True`, `False`
- **Operators:** `=>`
- **Comments:** Lines starting with `#`
- **JSON Blocks:** Content inside `{ ... }` is highlighted as JSON

## Contributing

Feel free to submit issues or pull requests on [GitHub](https://github.com/hidao80/vscode-powerautomate-desktop-syntax).

## License

This project is licensed under the MIT License. See [LICENSE.md](LICENSE.md) for details.
