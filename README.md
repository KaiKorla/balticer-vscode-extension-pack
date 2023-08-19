# korla-vscode-extension-pack

My favorite VSCode extensions.

# Manual install
Goto https://github.com/KaiKorla/korla-vscode-extension-pack/releases/latest and check for the latest version.
Replace {Version} with the latest version in the following commands.

## Windows
```console
~$ Invoke-WebRequest https://github.com/KaiKorla/korla-vscode-extension-pack/releases/download/{Version}/korla-vscode-extension-pack-{Version}.vsix
~$ code --install-extension korla-vscode-extension-pack-{Version}.vsix
 ```

## Linux
```console
~$ curl -O https://github.com/KaiKorla/korla-vscode-extension-pack/releases/download/{Version}/korla-vscode-extension-pack-{Version}.vsix
~$ code --install-extension korla-vscode-extension-pack-{Version}.vsix
 ```

## Mac
```console
~$ curl -O https://github.com/KaiKorla/korla-vscode-extension-pack/releases/download/{Version}/korla-vscode-extension-pack-{Version}.vsix 
~$ /Applications/Visual\ Studio\ Code.app/Contents/Resources/app/bin/code --install-extension korla-vscode-extension-pack-{Version}.vsix
 ```

# How to build from source
```console
~$ git clone https://github.com/KaiKorla/korla-vscode-extension-pack.git
~$ npm install
~$ npm install @vscode/vsce
~$ vsce package
 ```