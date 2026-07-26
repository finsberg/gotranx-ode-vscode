# gotranx-ode

This is a vscode extension for syntax highlighting of the GoTranX ODE language.
See https://github.com/finsberg/gotranx for more information about the language.

## Installation

This extension is distributed as a Visual Studio Code package (`.vsix`). You can easily download and install it directly from the GitHub Releases page.

### Option 1: Install via the VS Code Interface (Recommended)

1. Navigate to the [Releases page](https://github.com/finsberg/gotranx-ode-vscode/releases) of this repository.

2. Download the latest `.vsix` file (e.g., `gotranx-ode-0.0.1.vsix`) located under the Assets section of the latest release.

3. Open Visual Studio Code.

4. Open the Extensions view by clicking the Extensions icon in the Activity Bar on the left side of the window, or by pressing Ctrl+Shift+X (Cmd+Shift+X on macOS).

5. Click the Views and More Actions menu (the ... icon at the top right of the Extensions panel).

6. Select Install from VSIX... from the dropdown menu.

7. Locate and select the downloaded `.vsix` file to install it.

### Option 2: Install via the Command Line

If you prefer using the terminal, you can install the extension using the VS Code CLI:

1. Download the `.vsix` file from the Releases page.

2. Open your terminal or command prompt.

3. Run the following command, replacing the path with the actual location of your downloaded file:
```bash
code --install-extension path/to/downloaded/gotranx-ode-0.0.1.vsix
```

### Verifying the Installation

Once the installation is complete:

1. Open any `.ode` file in VS Code.

2. The editor should automatically recognize the file extension and apply the Gotranx ODE syntax highlighting.

3. You should see ODE listed as the active language mode in the bottom right corner of the VS Code status bar.

## License
MIT