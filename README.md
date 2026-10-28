<img
  src="https://raw.githubusercontent.com/stormphlegyas/vscode-decode-header/main/decode.png"
  width=128>

# Decode Header for VSCode

This extension integrates the [.decode](https://ecole-decode.fr/) school header in VS Code to easily include it in your source code files.

```bash
#******************************************************************************#
#                                                      .##################.    #
#                                                      ##############   ###    #
#    vscode-decode-header                              ##############   ###    #
#                                                      ########'        ###    #
#    By: student <student@ecole-decode.fr>             ######'  .###.   ###    #
#                                                      ######   #####   ###    #
#    Created: 2026/10/28 13:37:42 by student           ##   #.  '###'   ###    #
#    Updated: 2026/10/28 13:37:42 by student           ##   ###.        ###    #
#                                                      '##################'    #
#******************************************************************************#
```

## Install

You can install the extension by searching for "Decode Header" in the VS Code Extensions Marketplace or by launching Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and entering the command:

```
ext install stormphlegyas.decodeheader
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

The header will be automatically updated on save.


## Configuration

By default, the extension will import your **username** from environment variables and use `<username>@ecole-decode.fr` as **email**. However, you can override these values by specifying them in your *User Settings*:

```ts
{
  "decodeheader.username": string,
  "decodeheader.email": string
}
```

## Supported Languages

This extension supports a wide range of programming languages. For each language, it uses a specific delimiter to create the header. Here's a list of the supported languages:

- Assembly Language
- C
- C++
- CoffeeScript
- CSS
- Dockerfile
- F#
- Go
- Groovy
- Haskell
- HTML
- INI
- Jade
- Java
- JavaScript
- JavaScript React
- Kotlin
- LaTeX
- Less
- Lua
- Makefile
- Objective-C
- OCaml
- Perl
- Perl6
- PHP
- Plaintext
- PowerShell
- Python
- R
- Ruby
- Rust
- SASS
- SCSS
- ShellScript
- Solidity
- SQL
- Swift
- TypeScript
- TypeScript React
- Verse
- Vue
- XSL
- YAML

## Issues

In case of a bug, or missing feature, please create a [Github Pull Request](https://github.com/stormphlegyas/vscode-decode-header/pulls).

## Credits

Based on [vscode-42header](https://github.com/stormphlegyas/vscode-42header).

## License

MIT
