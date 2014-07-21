# Linux settings

## Installation

    git clone git@github.com:fdumoulin/dotfiles.git .dotfiles
    cd .dotfiles
    # create symlinks
    for file in *; do; ln -sv .dotfiles/$file ../.$file ; done;
