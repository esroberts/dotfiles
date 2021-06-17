# TMUX

This is my TMUX configuration, tested most recently with tmux v3.2.

## Pre-requisites
```
# see https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard for the skinny on why this is a
# must for sane copy/paste in Mac OS X.
brew install reattach-to-user-namespace
```

## Shell Alias
Set up this shell alias that will initiate your tmux session with your ideal console development
environment defined in `dev.conf`.
```
alias dev_tmux='tmux -f ~/dev.conf attach'
```

## dev.conf
This is where you set up your default windows and panes

## .tmux.conf
This file is where you put your key bindings, shortcuts, and look/feel that apply to 
all tmux sessions.


