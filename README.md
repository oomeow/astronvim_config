# AstroNvim config

**NOTE:** This is for AstroNvim v6+

> In `Linux wayland`, you should install `wl-clipboard`

## 🛠️ Installation

### 1. Make a backup of your current nvim and shared folder

#### Unix
```shell
mv ~/.config/nvim ~/.config/nvim.bak
rm -rf ~/.local/share/nvim
rm -rf ~/.local/state/nvim
rm -rf ~/.cache/nvim
```

#### Windows
```shell
# powershell
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
Remove-Item -Recurse -Force $env:LOCALAPPDATA\nvim-data

# nushell
mv $"($env.LOCALAPPDATA)\\nvim" $"($env.LOCALAPPDATA)\\nvim.bak"
rm -rf $"($env.LOCALAPPDATA)\\nvim-data"
```

### 2. Clone the repository

#### Unix
```shell
git clone https://github.com/oomeow/astronvim_config.git ~/.config/nvim
```

#### Windows
```shell
# powershell
git clone --depth 1 https://github.com/oomeow/astronvim_config.git $env:LOCALAPPDATA\nvim

# nushell
git clone --depth 1 https://github.com/oomeow/astronvim_config.git $"($env.LOCALAPPDATA)\\nvim"
```

### 3. Start Neovim

```shell
nvim
```
