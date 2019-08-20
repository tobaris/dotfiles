## dotfiles Tmux Zsh Vim

|software|version     |
|--------|------------|
|Tmux    |tmux 2.9a   |
|Vim     |IMproved 8.1|
|Zsh     |5.7.1       |

## Description

1. Install zsh vim tmux.
2. Copy the configuration file to your home directory.
3. Library installation

## Library installation

```
$ brew update
$ brew install vim python cmake go mono node rust

$ cd ~/
$ vim +PlugInstall +qall
$ cd .vim/plugged/YouCompleteMe/
$ /usr/bin/python2.7 ./install.py --all
```
