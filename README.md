# Config for NeoVim

## Steps to install

1. Clone this repo

```Bash
git clone https://github.com/minhthuc2502/nvim.git $HOME/.config/nvim
```

2. Install vim-plug: https://github.com/junegunn/vim-plug

3. Install all extension

```bash
# In this repo
nvim init.vim
# In nvim window
:PlugInstall
```
4. Restart nvim

## Config coc

1. Install autocompletion

```bash
# In nvim window
:CocInstall coc-clangd
:CocCommand clangd.install
```

## Install package not installed
1. ``ripgrep``
```bash
sudo snap install ripgrep --classic
```