# My Dotfiles

This repo is to maintain my own MacOS dotfiles. The configuration is largely adapted from [Anish's](https://github.com/anishathalye/dotfiles/), and I only modify for my own convenience.

Run `install` to automatically set up the development environment. Note that the install script is idempotent: it can safely be run multiple times.

Dotfiles uses [Dotbot][dotbot] for installation, which is also developed by Anish. Thanks for his work!

Making Local Customizations
---------------------------

You can make local customizations for some programs by editing these files:

* `vim` : `~/.vimrc_local`
* `emacs` : `~/.emacs_local`
* `zsh` / `bash` : `~/.shell_local_before` run first
* `zsh` : `~/.zshrc_local_before` run before `.zshrc`
* `zsh` : `~/.zshrc_local_after` run after `.zshrc`
* `zsh` / `bash` : `~/.shell_local_after` run last
* `git` : `~/.gitconfig_local`
* `hg` : `~/.hgrc_local`
* `tmux` : `~/.tmux_local.conf`
