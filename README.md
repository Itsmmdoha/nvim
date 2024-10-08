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

### Mappings

Find detailed docs [here](https://docs.astronvim.com/mappings)

> Custom Mapping: `kj` has been Mapped to `<Esc>` in insert mode
> with:
> ```lua
> vim.keymap.set("i", "kj", "<Esc>", options)
> ```
> in the init.lua file

This is a fork of the original [AstroNvim Repository](https://github.com/AstroNvim/template)
