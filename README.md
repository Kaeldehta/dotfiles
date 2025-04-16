# Dotfiles

## Setup
Using the "bare repository and alias method" from [Ask Hacker News: What do you use to manage your dotfiles?](https://news.ycombinator.com/item?id=11071754)
```
git clone --bare <git-repo-url> $HOME/.dotfiles
alias dotfiles='/usr/bin/git --git-dir="$HOME/.dotfiles/" --work-tree="$HOME"'
dotfiles checkout
dotfiles config --local status.showUntrackedFiles no
```
