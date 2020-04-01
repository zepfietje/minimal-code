<div align="center"><img src="screenshots/empty-light.png" width="400"></div>

# Minimal Code

Minimal Code is a set of extensions, settings and keyboard shortcuts that turns Visual Studio Code into a minimal and productive development/writing environment.  
It's focused on minimizing distractions, reducing mouse usage and optimizing the overall workflow.

## Installation

1. Install [Visual Studio Code](https://code.visualstudio.com/Download).
   ```console
   $ brew cask install visual-studio-code
   ```
2. Install [Customize UI](https://marketplace.visualstudio.com/items?itemName=iocave.customize-ui) extension.
   ```console
   $ code --install-extension iocave.customize-ui
   ```
3. Install [Atom One Light Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onelight) extension.
   ```console
   $ code --install-extension akamud.vscode-theme-onelight
   ```
4. Install [Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark) extension.
   ```console
   $ code --install-extension akamud.vscode-theme-onedark
   ```
5. Install [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) extension.
   ```console
   $ code --install-extension pkief.material-icon-theme
   ```
6. Install [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font.
   ```console
   $ brew tap homebrew/cask-fonts
   $ brew cask install font-jetbrains-mono
   ```
7. Copy the contents of [`src/settings.json`](src/settings.json) to your settings file (search **Preferences: Open Settings (JSON)** using the Command Palette).

## Screenshots

![empty light](screenshots/empty-light.png)
![empty dark](screenshots/empty-dark.png)
![code light](screenshots/code-light.png)
![code dark](screenshots/code-dark.png)
