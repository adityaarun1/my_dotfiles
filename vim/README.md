# VIM configurations

Requirement `vim > 0.8`

Install [vim-plug](https://github.com/junegunn/vim-plug)

Install [coc.nvim](https://github.com/neoclide/coc.nvim) for auto suggestions.

Run `yarn install` in the `$HOME/.vim/config` folder to install yarn dependecies. Specific
coc extensions can be installed using `:CocInstall coc-json coc-pyright coc-xml`. To configure
the extensions, run `:CocConfigure` andd appropriate changes.

Directory Structure

`$HOME/.vim` <br>
&nbsp;&nbsp;|-- `autoload` <br>
&nbsp;&nbsp;|-- `backup` <br>
&nbsp;&nbsp;|-- `colors` <br>
&nbsp;&nbsp;|-- `config` > `coc.vim` <br>
&nbsp;&nbsp;|-- `plugged` <br>
