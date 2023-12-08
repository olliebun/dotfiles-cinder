# dotfiles-cinder

Dotfiles for my Windows desktop running Ubuntu using WSL2.


```sh
git clone --bare git@github.com:olliebun/dotfiles-cinder.git ~/.dotfiles
alias dgit='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
dgit config status.showUntrackedFiles no
```
