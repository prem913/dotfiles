# My Dotfiles

## Configuration

### stow

- This dotfiles repository uses stow to manage symlinks
- Install with `pacman -S stow`
- To add all sym links use command `stow .` in dotfiles directory

### zsh

- Uses zinit as plugin manager
- Requires
  - zoxide (for arch `pacman -S zoxide`)
- Run `source ~/.zshrc`. zinit will install plugins automatically on first run
