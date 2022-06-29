<p align="center">
   <picture align="center">
      <source media="(prefers-color-scheme: light)" srcset="screenshots/code-light.png">
      <source media="(prefers-color-scheme: dark)" srcset="screenshots/code-dark.png">
      <img src="screenshots/code-light.png" width="400">
   </picture>
</p>

[![Starware](https://img.shields.io/badge/⭐-Starware-f5a91a?labelColor=black)](https://github.com/zepfietje/starware)

# Minimal Code

Minimal Code is a set of extensions, settings and keyboard shortcuts that turns Visual Studio Code into a minimal and productive development environment.  
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
3. Install [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme) extension.
   ```console
   $ code --install-extension github.github-vscode-theme
   ```
4. Install [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font.
   ```console
   $ brew tap homebrew/cask-fonts
   $ brew cask install font-jetbrains-mono
   ```
5. Copy the contents of [`src/settings.json`](src/settings.json) to your settings file (search **Preferences: Open Settings (JSON)** using the Command Palette).

## Screenshots

![code light](screenshots/code-light.png)
![code dark](screenshots/code-dark.png)
![empty light](screenshots/empty-light.png)
![empty dark](screenshots/empty-dark.png)

## Starware

Minimal Code is Starware.  
This means you're free to use the project, as long as you star its GitHub repository.  
Your appreciation makes us grow and glow up. ⭐
