# VS Code Extension for goose

This runs <a href="https://github.com/square/goose">goose</a> in your VS Code instance every time you open it, and lets you interact with goose either directly, or you can highlight sections of code, ask questions about it, or even ask it to change the code or do work with it.

> [!IMPORTANT]  
> This requires that you have <a href="https://github.com/square/goose">goose</a> installed and running for this to work. 
> **This is a work in progress as we explore what modalities we want from goose an an IDE. Use with caution.**

## Table of Contents

- [In Action](#in-action)
- [Running from Source](#running-from-source)
- [Installation into VS Code from Source](#installation-into-vs-code-from-source)
  - [Packaging the Extension](#packaging-the-extension)
  - [Installing the Extension](#installing-the-extension)
  - [Uninstalling the Extension](#uninstalling-the-extension)

## In Action

![action1](https://github.com/user-attachments/assets/7cecc165-72c3-4936-977e-f7b9cf2c3906)

![action2](https://github.com/user-attachments/assets/2425f54d-c88b-4ef0-b00e-1ceac9a8dcd5)
![action3](https://github.com/user-attachments/assets/e35296d8-aaf7-43e1-915c-6fb86ed05cb9)


Can ask it to enhance code, can run commands, take action, test and more:

![action4](https://github.com/user-attachments/assets/c6f00750-0f28-4683-84a1-765740c72fba)


## Running from Source

Open this repo via `code .` and then press F5 to run a new workspace with this in it. 

## Installation into VS Code from Source

### Packaging the Extension

To package the extension, run the following command:

```sh
npm install 
npm run package
```

This will create a `.vsix` file in the root directory of the project.

### Installing the Extension

To install the packaged extension, use the following command:

```sh
code --install-extension goose-vscode-1.0.0.vsix
```

### Uninstalling the Extension

To uninstall the extension, use the following command:

```sh
code --uninstall-extension block.goose-vscode
```
