# Gofra for VS Code

Extension for Gofra programming language in Visual Studio Code

## Features

- Syntax Highlighting: Support for `.gof` file syntax.

## Installation

### Manual Installation from Source

1. Clone the Repository:

```bash
git clone https://github.com/kirillzhosul/gofra-vscode
```

2. Package the Extension:
   You need to have Node.js and the vsce (Visual Studio Code Extensions) tool installed.

```bash
npm install -g @vscode/vsce
vsce package
```

This command will create a .vsix file in the directory.

3. Install in VS Code:

- Open VS Code.
- Go to the Extensions view (Ctrl+Shift+X / Cmd+Shift+X).
- Click the "..." menu in the top-right of the Extensions panel and select Install from VSIX....
- Navigate to and select the .vsix file you created in the previous step.
- Reload VS Code when prompted.
