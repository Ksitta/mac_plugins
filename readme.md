# Plugins & Command to make mac easy to use

Here are some Mac plugins or commands I've collected to get used to when switching from Windows

## Necessary Software

1. [Homebrew](https://brew.sh/)
2. [iRightMouse](https://www.irightmouse.com/)
3. [Snipaste](https://zh.snipaste.com/)
4. [Linearmouse](https://linearmouse.org/)
5. [Alfred](https://www.alfredapp.com/)
6. [Stretchly](https://hovancik.net/stretchly/)
7. [Karabiner](https://karabiner-elements.pqrs.org/)

   See myshortcut.json for my configuration
8. [iTerm2](https://iterm2.com/)

## Settings

### Show breadcrumbs navigator in finder

Finder > View > Show Path Bar

### Auto switch input method

System Preferences > Keyboard > Input Sources > Automiacally switch to a document's input source

### Use ziranma(自然码双拼)

defaults write com.apple.inputmethod.CoreChineseEngineFramework shuangpinLayout 5

### zsh config

see .zshrc

### Globally ignore .DS_Store

```bash
echo ".DS_Store" >> ~/.gitignore_global
```

add following to .zshrc

```bash
[core]
   excludesfile = /Users/frw/.gitignore">> ~/.gitconfig_global
```
