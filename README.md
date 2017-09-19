# vim-dotfiles

![vim](https://i.imgur.com/j5zBgjW.png)

## Prerequisites

1. vim (version 8)
2. vim-plug, Minimalist Vim plugin manager that can be found [here](https://github.com/junegunn/vim-plug). Plug is awesome and it can be installed as easy as copy/pasting single curl command! 

## Plugins

1. [gruvbox](https://github.com/morhetz/gruvbox)

Gruvbox is quite nice colour theme that supports various filetypeis highlighting. Also, it might be good for your eyes (it is inspired by Solarized and other themes that actually have that as one of the goals)!

2. [vim-sensible](https://github.com/tpope/vim-sensible)

As name suggests, sensible set of defaults for vim. Good even for people that doesn't want to go over this complete procedure. Seriously, give it a check!

3. [delimitMate](https://github.com/Raimondi/delimitMate)

Automatic closing of quotes, parenthesis and etc. This module can make your life easier if you are developer.

4. [indentLine](https://github.com/Yggdroot/indentLine)

This plugin will quite nicely indicate indentation level that you are currently working on. Especially useful for languages that are sensitive to this. 

5. [jedi-vim](https://github.com/davidhalter/jedi-vim)

This plugin provides autocompletion for vim.

6. [pydoc.vim](https://github.com/fs111/pydoc.vim)

Python documentation. If you are Python developer, you may want to give a chance to this plugin. 

7. [supertab](https://github.com/ervandew/supertab)

Plugin that allows you to use < TAB > for insert completion. Quite useful.

8. [tagbar](https://github.com/majutsushi/tagbar)

Class outline viewer for vim. Enables easy navigation through file structure. 

9. [vim-airline](https://github.com/vim-airline/vim-airline)

Airline is awesome status/tabline that indicates all the right updates/data about file being worked on.

10. [vim-flake8](https://github.com/nvie/vim-flake8)

Style and syntax checher for Python code. If you are Python developer you may want this plugin.

11. [vim-quickrun](https://github.com/thinca/vim-quickrun)

Want to quickly run code that you just wrote in another split window? This is plugin for you. 

## Setup

1. Clone this repo:
```
git clone https://github.com/kemals/vim-dotfiles
```
2. Backup current .vimrc if there is one:
```
cp ~/.vimrc ~/vimrc.bac
```
3. Copy cloned config file as new .vimrc:
```
cp vim-dotfiles/config/vimrc ~/.vimrc
```
4. Open the newly copied file with vim:
```
vim ~/.vimrc
```
5. Once the vim opens the file, in Normal mode:
```
:PlugInstall
```
6. Plug will install all the modules listed in the .vimrc and once it completes just close the file:
```
:qa!
```
7. Profit! 
