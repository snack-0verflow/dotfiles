# Homebrew

> [!NOTE]
> Quick install of brew

```sh
/bin/bash -c "$(curl -fsSL <https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh>)"
```

# Cli tools

```sh
brew install neovim \
 glow \
 tmux \
 exa \
 fzf \
 ripgrep \
 fd \
 zoxide \
 thefuck \
 lazygit \
 gitui \
 asdf \
 watchman
```

# Applications

```sh
brew install --cask \
 brave-browser \
 visual-studio-code \
 spotify \
 iterm2 \
 cursor \
 nikitabobko/tap/aerospace
```

### Shell

- [oh-my-posh](https://ohmyposh.dev/docs/installation/macos)

### Vim

- [lazy-nvim](https://www.lazyvim.org/installation)

### iTerm2

- [theme](https://github.com/hwyncho/ayu-iTerm)

## Vscode

### Backup extensions

```sh
code --list-extensions >> vs_code_extensions_list.txt
```

### Restore extensions

```sh
cat vs_code_extensions_list.txt | xargs -n 1 code --install-extension
```

### Uninstall extensions

```
code --list-extensions | xargs -n 1 code --uninstall-extension
```
