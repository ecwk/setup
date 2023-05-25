# Setup

## installs
- `pyenv`
- `nvm`

## dotfiles

- tmux
  - no external downloads
  - files
    - `.tmux.conf`
- zsh
  - external downloads
    - `ohmyzsh`
    - `powerlevel10k`
    - `command-not-found`
    - `golang-chroma`
    - `ripgrep`
    - `lsd`
  - files
    - `.zshrc`
- nvim
  - `nvchad`
    - no further configs so I'll not include the config folder

## gnome
- gnome compatibility with Parsec immersive mode
  - gsettings set org.gnome.mutter.wayland xwayland-allow-grabs true
    - allows windows to capture global key inputs
  - gsettings set org.gnome.mutter.wayland xwayland-grab-access-rules "['parsecd']"
    - allows these specific windows to capture window-based key binds
