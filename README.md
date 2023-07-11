# Note to self:
- this dotfiles are configured on Pop!_OS with i3 so it may have some distro-related dependencies installed that I don't know how I installed because I'm dumb af on linux right now
- I uninstalled Pop!_OS because of some package errors, but I might get back to it lmao (ima just distro hop for a sec)
- gonna try Arch so I can say I use Arch btw to flex my catppuccin mocha configs which can just be installed to any other distro lmao
- make the machine configured for C# .NET development in Linux
- update (July 11, 2023): going to try Endeavour OS or archinstall with Hyprland as WM

### Necessary Installations:
- Nerd Fonts: JetBrainsMono NF, RobotoMono NF, MaterialIcons?, Feather?

### Terminal
- Alacritty
- will try Kitty
Reason: cannot make Alacritty transparent idk why opacity do not work on i3 wtf, but works on Pop!_OS Gnome (Cosmic) though

### Sxhkd --> Shortcut Keys Manager, independent keybindings

### Nvim
- install via pacman (if using Arch) or using appimage for latest install
- install lazyvim starter
- change theme to catppuccin-mocha
- configure keymaps
- import languages in lazy.lua

### WM
- if using i3, change the keybindings for window management (see i3 config)
- Hyprland, also change keybindings if necessary

### Global Search
- Rofi, try to configure theme
- keybind it (bindsym in i3, in Hyprland idk look at docs)

### Themes, Icons, and Other Essentials
- Install Breeze
- File System --> Nautilus, Thunar, or idk any

### Shell
- zsh --> oh-my-zsh
- oh-my-zsh catppuccin mocha theme
- try to look into fish shell

### Bar
- Polybar
- Waybar --> if using Hyprland, which is most likely I will be using

### When installed:
- ensure git is installed, then configure git config --global user.name and user.email
- Make input devices work (microphone, camera, etc.) --> xinput
- Wallpaper enable via feh or nitrogen (see i3 config for bindsym)
- Make wifi and network configured
- Time and date
- Battery percentage on polybar or waybar or any
- Audio (idk wtf look at i3 configs) and Brightness configs (brightnessctl or light)
- ssh-agent (get new sha256 key in github)
