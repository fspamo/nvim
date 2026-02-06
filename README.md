# A ligthweight Neovim rice that does pretty much all you need.

**NOTE:** NPM and [Nerdfont](https://www.nerdfonts.com/) is required.

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Clone the repository

```shell
git clone https://github.com/fspamo/nvim ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```
#### Auto-completion setup

Install all the plugins using 
```
:PlugInstall
```

#### Auto-completion setup

```Python
sudo apt install flake8 black
```
```C
sudo apt install flake8 black
```
```Then inside Neovim
:CocInstall coc-clangd coc-pyright
```

**NOTE:** Couple optional shortcuts are assigned to different key combinations. (Such as Space+s to save the file and Space+f to format) 
