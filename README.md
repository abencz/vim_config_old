# Vim Configuration

This is my accrued configuration from using Vim over the last 5 years. As a
result there a lot of warts and older stuff - you may want to prune `vimrc` a
bit before using. Some of the ugliness is for configuring different defaults in
Windows, OSX, and Linux (and in GUI vs. terminal Vim) because I use all three
OSs on a regular basis.

## Installation
In OSX/Linux it's generally enough to clone this repository to ~/.vim and
create a symlink to vimrc, like:

    git clone git@github.com:abencz/vim_config.git ~/.vim
    ln -s ~/.vim/vimrc ~/.vimrc

You will probably also want to initialize and update the submodules:

    git submodule init
    git submodule update

Windows has additional complications - usually I end up cloning the
configuration over the `vimfiles` directory wherever Vim is installed. The
`vimrc` file must then be copied into place manually. There may be a better
solution I'm not aware of.


