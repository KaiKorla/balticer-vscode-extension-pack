# balticer-vscode-extension-pack

My favorite VSCode extensions.

# Marketplace install
Todo

# Manual install
Goto https://github.com/KaiKorla/balticer-vscode-extension-pack/releases/latest and check for the latest version.
Replace {Version} with the latest version in the following commands.

## Windows
```console
~$ Invoke-WebRequest https://github.com/KaiKorla/balticer-vscode-extension-pack/releases/download/{Version}/balticer-vscode-extension-pack-{Version}.vsix
~$ code --install-extension balticer-vscode-extension-pack-{Version}.vsix
 ```

## Linux
```console
~$ curl -O https://github.com/KaiKorla/balticer-vscode-extension-pack/releases/download/{Version}/balticer-vscode-extension-pack-{Version}.vsix
~$ code --install-extension balticer-vscode-extension-pack-{Version}.vsix
 ```

## Mac
```console
~$ curl -O https://github.com/KaiKorla/balticer-vscode-extension-pack/releases/download/{Version}/balticer-vscode-extension-pack-{Version}.vsix 
~$ /Applications/Visual\ Studio\ Code.app/Contents/Resources/app/bin/code --install-extension balticer-vscode-extension-pack-{Version}.vsix
 ```

# How to build from source
```console
~$ git clone https://github.com/KaiKorla/balticer-vscode-extension-pack.git
~$ npm install
~$ npm install @vscode/vsce
~$ vsce package
 ```