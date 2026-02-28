# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

# Installation
`cd ~/.config/; git clone git@github.com:kyflores/nvim-cfg.git nvim`
### Plugin dependencies
These programs need to be installed separately for plugins to call.
* rust-analyzer
* [clangd](https://github.com/clangd/clangd)
* basedpyright
* npm
* [lazygit](https://github.com/jesseduffield/lazygit) (run it once to generate config)

## With brew
Some of these packages aren't distributed by apt but can be found in brew.
```
# Packages for LSPs, and neovim itself
brew install neovim lazygit npm basedpyright rust
# Example of installing a nerdfont for lazyvim icons to work. 
brew install --cask font-jetbrains-mono-nerd-font
# Example of setting the fonts as terminal default
gsettings set org.gnome.Ptyxis font-name 'JetBrainsMono Nerd Font 10'
```

# Reset Lazy
```
rm -rf ~/.local/share/nvim
rm -rf ~/.local/state/nvim
rm -rf ~/.cache/nvim
```


# Most used keymaps
C -> ctrl, S -> shift, A -> alt, leader -> space (by default)
| Key | Description |
| --- | ----------- |
| \<C-h\> | Go to left window |
| \<C-j\> | Go to lower window |
| \<C-k\> | Go to upper window |
| \<C-l\> | Go to right window |
| \<S-h\> or [b | Previous tab |
| \<S-l\> ]b | Next tab |
| \<leader\><\leader\>| Search for files |
| \<leader\>bd| Close tab |
| \<leader\>bD| Close and window |
| \<leader\>bo| Close other tabs |
| \<leader\>E| Toggle explorer |
| \<leader\>qq| Quit all |
| \<leader\>ft| Terminal in root (close if already open) |
| \<leader\>fT| Terminal in cwd (close if already open) |
