# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

# Installation
`cd ~/.config/; git clone git@github.com:kyflores/nvim-cfg.git nvim`
### Plugin dependencies
These programs need to be installed separately for plugins to call.
* rust-analyzer
* [clangd](https://github.com/clangd/clangd)
* pyright
* npm
* [lazygit](https://github.com/jesseduffield/lazygit) (run it once to generate config)

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
