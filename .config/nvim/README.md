# LazyVim Configuration

This directory contains a default [LazyVim](https://www.lazyvim.org/) configuration for Neovim.

## Structure

```
.config/nvim/
├── init.lua                    # Entry point - bootstraps LazyVim
└── lua/
    ├── config/
    │   ├── autocmds.lua       # Custom autocommands
    │   ├── keymaps.lua        # Custom key mappings
    │   ├── lazy.lua           # lazy.nvim plugin manager setup
    │   └── options.lua        # Neovim options
    └── plugins/
        └── example.lua        # Example plugin configuration
```

## Installation

1. Make sure you have Neovim 0.9.0 or later installed
2. Symlink or copy this configuration to your Neovim config directory:
   ```bash
   ln -s ~/.config/nvim ~/path/to/dotfiles/.config/nvim
   ```
   Or on a fresh install:
   ```bash
   cp -r .config/nvim ~/.config/
   ```
3. Start Neovim - plugins will be installed automatically on first launch

## Features

LazyVim comes with:
- 📦 Lazy loading for fast startup times
- 🎨 Beautiful default colorscheme (tokyonight)
- 🔍 Telescope for fuzzy finding
- 🌳 Neo-tree file explorer
- 💻 LSP support with mason.nvim
- ✨ Treesitter for better syntax highlighting
- 🔧 Which-key for keybinding hints
- And much more!

## Customization

- Add your custom plugins in `lua/plugins/`
- Modify keymaps in `lua/config/keymaps.lua`
- Adjust options in `lua/config/options.lua`
- Add autocommands in `lua/config/autocmds.lua`

For more information, visit [LazyVim Documentation](https://www.lazyvim.org/)
