# My DotFile for i3 
## Screenshots
![Alt text](/screenshots/1.png?raw=true)
## Installation
### Install packages on Void Linux
```bash
    sudo xbps-install -S i3 alacritty rofi feh cli-visualizer maim
```
### Clone the repository
```bash

    git clone https://github.com/Filang666/MyI3DotFileGruvbox.git ~/.dotfiles
    cd ~/.dotfiles
```
###    Backup your existing configs (optional but recommended)
   
```bash
    mv ~/.config/i3 ~/.config/i3.bak
    mv ~/.config/alacritty ~/.config/alacritty.bak
    mv ~/.config/rofi ~/.config/rofi.bak
    mv ~/.config/vis ~/.config/vis.bak
```
###    Symlink the configuration files
   
```bash
    ln -sf ~/.dotfiles/i3 ~/.config/i3
    ln -sf ~/.dotfiles/alacritty ~/.config/alacritty
    ln -sf ~/.dotfiles/rofi ~/.config/rofi
    ln -sf ~/.dotfiles/vis ~/.config/vis
```
###    Or use script
```bash
    chmod +x install.sh
    ./install.sh
``` 
###    Reload i3
    Press $mod+Shift+r to restart i3 in place, or log out and back in.
