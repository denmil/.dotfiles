# .dotfiles

This repository contains all my dotfiles. I am currently using MacOS; stuff should work, but double-check before blindly applying on another OS.

I use stow to manage the symlinks. To install stow:

```bash
brew install stow
```

To generate the symlinks, make sure that the .dotfiles repo is cloned in the home directory, then:

```bash
cd ~/.dotfiles
stow .
```


To remove the symlinks:

```bash
cd ~/.dotfiles
stow -D .
```

Quick guide to stow: https://tamerlan.dev/how-i-manage-my-dotfiles-using-gnu-stow/

