# Power Automate Desktop Syntax Highlighting

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Ask DeepWiki](https://img.shields.io/badge/Ask_DeepWiki-007ec6?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAACXBIWXMAAAPoAAAD6AG1e1JrAAACIUlEQVRYw%2B2XP2gUQRTGv7d3JhYWQawkIBaCVWzETos0gmAnVoKNTSoLK0E7EQQrC20sBVFBtLPQRgTBtBaKjYgIQUSxiJq7fT%2BLvCGPJZdNLt4dQj5Y3u7sznzfzLw%2Fs9IO%2FicANiniCujEfWdsQgBLxAbsbraPZcmBfcAt4DNwKQsZNfEUsAB8YRV12LfA6ZHuedg7AO7ed%2Fc%2BUBcbQhbiu%2B6wXIM6EnZWkszMJe2Ke0n6I2la0v51hFeSMLN6OwIK6jJwEBdUYb2MAxRSz6sY4geiahFgLe1Hwq6YWe3us8AN4FQQU4QM64SPY69Xyr43fADgNjAPXHb3peSsD4FDQ0VLEjAHvIhBPS6AHvA1bBO9JPAXcHFbIRtJ5yzwIQZ9CZwAusDJENIkLqsG8DpNyIZJwSUk9wLHgakcesC1JCCjiHm1kYDNOEjptCxpSVK%2F8f73OFLxPLAYM3oCzEX7MXf%2FlJbc%2F8kWpA4HgQdpYI9IWAbeh83whi84cHXL%2B58EPBoQhnmm94EzwE3gZ2p%2FDhzdbhg%2BTaRr01x7ftb4%2FjBwFzjXrCvDpmLW9crVLNeR9CaapoGemb2TdCERW1tNaBNQ8jktwmozqwtpqRNtdWAjARYk39IS12ZWRX7vmJmA71nQZgi36gN7gCvAj5xc3P0jcH7kx7Ik5IC73wsh14GZsZySow5002l4Jr0b6%2Bm4eSyvpAn8lEzsx2QHo8RfUrlN%2BuPq4ksAAAAASUVORK5CYII%3D&labelColor=010101)](https://deepwiki.com/hidao80/vscode-powerautomate-desktop-syntax)

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
