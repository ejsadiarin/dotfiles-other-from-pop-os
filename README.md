# Note to self:
- this dotfiles are configured on Pop!_OS with i3 so it may have some distro-related dependencies installed that I don't know how I installed because I'm dumb af on linux right now
- I uninstalled Pop!_OS because of some package errors, but I might get back to it lmao (ima just distro hop for a sec)
- gonna try Arch so I can say I use Arch btw to flex my catppuccin mocha configs which can just be installed to any other distro lmao
- make the machine configured for C# .NET development in Linux

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

### Global Search
- Rofi, try to configure theme

### Themes, Icons, and Other Essentials
- Install Breeze
- File System --> Nautilus, Thunar, or idk any

### Shell
- oh-my-zsh
- oh-my-zsh catppuccin mocha theme

### Bar
- Polybar
- or Waybar idk

### When installed:
- ensure git is installed, then configure git config --global user.name and user.email
- Make input devices work (microphone, camera, etc.) --> xinput
- Wallpaper enable via feh or nitrogen (see i3 config for bindsym)
- Make wifi and network configured
- Time and date
- Battery percentage on polybar or waybar or any
- Audio (idk wtf look at i3 configs) and Brightness configs (brightnessctl or light)
- ssh-agent (get new sha256 key in github)
