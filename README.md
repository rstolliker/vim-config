# vim-config
Personal vim configuration files, mainly, .vimrc and setup script

## Usage
First, clone the repo to the .vim folder.

`git clone https://github.com/rstolliker/vim-config.git ~/.vim`

Next, install Vundle and setup .vimrc

`bash setup install`

You will get an error that "solarized" cannot be found, this is okay and will go away after Vundle initializes.

If you ever need to clean the folder, run
`bash setup clean`
which will delete all bundle folders and remove the symlink to .vimrc

