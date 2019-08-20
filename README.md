## dotfiles Tmux Zsh Vim

|------|------------|
|Tmux  |tmux 2.9a   |
|Vim   |IMproved 8.1|
|Zsh   |5.7.1       |

## Library installation

```
brew update
brew install vim python cmake go mono node rust

cd ~/
vim +PlugInstall +qall
cd .vim/plugged/YouCompleteMe/
/usr/bin/python2.7 ./install.py --all
```
