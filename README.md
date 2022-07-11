# vimconfig
This is my vimconfig file for development on VIM

1. It requires the Plug module to be setup. Please follow the steps mentioned below in the link.
   https://github.com/junegunn/vim-plug
2. If you are using NeoVim then run these commands
   a. touch ~/.config/nvim/init.vim
   b. in init.vim add following contents
   ```vi
    set runtimepath^=~/.vim runtimepath+=~/.vim/after
    let &packpath = &runtimepath
    source ~/.vimrc 
   ```
3. Copy the .vimrc file to the home directly.
3. ```vi
    :PlugInstall
   ``` (this command should install all the necessary Plugins)

