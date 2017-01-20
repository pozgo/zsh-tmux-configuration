### zsh-tmux-configuration
This repository contains information on how easily to configure mac/linux terminal to be much more informative and easy to work with. It's based on ZSH as main shell and Tmux using some plugins both for zsh and tmux.

If you don't want to spend too much time configuring it and just want to start using it run below two commands and all will configure itself to look more or less as on screens

![Screen](https://raw.githubusercontent.com/pozgo/zsh-tmux-configuration/master/images/screen.png)

### Install ZSH and configure themes and plugins

    sh -c "$(curl -fsSL https://gist.githubusercontent.com/pozgo/4bd5e1357cffa24833130da6b287cd1d/raw/a0c28ff70326c03f6696efd452e688a46ac610b4/zsh-install.sh)"

### Install Tmux and configure themes and plugins

    sh -c "$(curl -fsSL https://gist.githubusercontent.com/pozgo/bd5fe0de44dd0793d96d6a400f061b54/raw/7deddaa765d9794947d3f4d0d5c8d5a91a228fa4/tmux-install.sh)"

**After the installation run tmux with command `tmux news -s MY_NAME` and use prefix key to enable tmux console and install plugins (ctrl+a I)**

![Run](https://raw.githubusercontent.com/pozgo/zsh-tmux-configuration/master/images/run.gif)
