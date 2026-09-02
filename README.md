## VS Code extension for Gofra

The extension is currently available by installing it directly from the source. We are working on publishing it to the Visual Studio Code Marketplace for easier installation.

#### Manual Installation from Source

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

#### Features

- Syntax Highlighting: Support for `.gof` file syntax.
