# Codebase AI Visual Studio Code Extension

This repository contains the source code for the VS Code extension developed by our team. The extension enhances your coding experience in Visual Studio Code by providing intelligent code suggestions. It leverages OpenAI's powerful GPT models to offer context-aware code suggestions.

## Features

- Intelligent code suggestions based on the entire codebase
- Seamless integration into your [Visual Studio Code IDE](https://code.visualstudio.com)

## VS Code API

### `vscode` module

- [`commands.registerCommand`](https://code.visualstudio.com/api/references/vscode-api#commands.registerCommand)
- [`window.showInformationMessage`](https://code.visualstudio.com/api/references/vscode-api#window.showInformationMessage)

### Contribution Points

- [`contributes.commands`](https://code.visualstudio.com/api/references/contribution-points#contributes.commands)

## Running the Sample

Guide for this sample: https://code.visualstudio.com/api/get-started/your-first-extension.

- Run `npm install` in terminal to install dependencies
- Run the `Run Extension` target in the Debug View. This will:
  - Start a task `npm: watch` to compile the code
  - Run the extension in a new VS Code window
