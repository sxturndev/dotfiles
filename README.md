# dotfiles
Personal dotfiles for my Lenovo Thinkpad A485, WIP

# Info
- OS: Arch Linux
- WM: qtile
- Terminal: kitty
- Browser: Firefox
- File Manager: Nemo & Ranger
- Fetch: neofetch
- Compositor: Picom

# Screenshots
...

# Installation
- `git` and GNU `stow` packages are required.

1. Clone into $HOME directory:
```bash
git clone https://github.com/sxturndev/dotfiles.git ~
```
2. Run `stow` to symlink all config files:
```bash
stow */
```

For specific programs, simply:
```bash
stow qtile
```
