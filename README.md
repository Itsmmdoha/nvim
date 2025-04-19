# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

## Installation

### Requirements
  1. Nerd Font (JetBrains Mono is my favorite)
  2. Neovim v0.9.5+ (Not including nightly)

Make a backup of your current nvim config (if exists)

```shell
mv ~/.config/nvim ~/.config/nvim.bak
```

Clean neovim folders (Optional but recommended)

```shell
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

Clone the repo

```shell
git clone  https://github.com/itsmmdoha/nvim ~/.config/nvim
rm -rf ~/.config/nvim/.git
nvim
```

### Custom Keymaps:

>```lua
>vim.keymap.set("i", "kj", "<Esc>", { desc = "Escape insert mode" })
>
> vim.keymap.set('t', 'kj', [[<C-\><C-n>]], { desc = "Terminal escape with kj" })
> ```

