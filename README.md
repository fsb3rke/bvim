# bvim 🦖

## INSTALLATION
### Linux/MacOS

<li>Make a backup of your current Neovim files:</li>

```sh
# required
mv ~/.config/nvim{,.bak}

# optional but recommended
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```

<li>Clone the starter</li>

```sh
git clone https://github.com/fsb3rke/bvim ~/.config/nvim
```

<li>Remove the `.git` folder, so you can add it to your own repo later</li>

```sh
rm -rf ~/.config/nvim/.git
```

<li>Start Neovim!</li>

```sh
nvim
```

### Windows

<li>Make a backup of your current Neovim files:</li>

```sh
# required
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak

# optional but recommended
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
```

<li>Clone the starter</li>

```sh
git clone https://github.com/fsb3rke/bvim $env:LOCALAPPDATA\nvim
```

<li>Remove the `.git` folder, so you can add it to your own repo later</li>

```sh
Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
```

<li>Start Neovim!</li>

```sh
nvim
```
