# basic09 README

This is a TextMate configuration for support of Basic09, a retro programming language for OS9.

## Features

Provides highlighting for Basic09 source code.

## Known Issues

No known issues

## Release Notes

### 1.0.0

Initial release of the language configuration.

#### Installing the extension in VSCode

To permanently enable the Basic09 syntax highlighting, you must install the extension locally in your main VS Code environment:

Package the Extension: Open your project folder in the terminal and use the VS Code Extension Manager (vsce) to create a package file (.vsix).

```bash
# (If you don't have vsce)
npm install -g vsce

# Create the package file (e.g., basic09-1.0.0.vsix)
vsce package
```

Install the VSIX: Open your regular VS Code window and go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).

Click the three dots menu (...) at the top right of the Extensions panel, and select Install from VSIX....

Navigate to your project folder and select the .vsix file you just created.

Once installed this way, the Basic09 syntax highlighting will be available permanently in your main VS Code sessions, just like any other extension you download from the marketplace.