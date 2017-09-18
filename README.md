# vim-dotfiles

### Prerequisites

1. Install vim 8 (required)
2. Install vim-plug, Minimalist Vim plugin manager that can be found here. It is awesome and it can be installed as easy as copying and pasting single curl command! 

### vim setup

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

### Installed plugins

1. [gruvbox](https://github.com/morhetz/gruvbox)
Gruvbox is quite nice colour theme that supports various filetype highlighting. Also, it might be good for your eyes!
2. [vim-sensible](https://github.com/tpope/vim-sensible)1 
As name suggests, sensible set of defaults for vim. Good even for people that doesn't want to go over this complete procedure. Seriously, give it a check!
3. [delimitMate](https://github.com/Raimondi/delimitMate)
Automatic closing of quotes, parenthesis and etc. This module can make your life easier if you are developer. 
4. [indentLine](https://github.com/Yggdroot/indentLine)
This plugin will quite nicely indicate indentation level that you are currently working on. Especially useful for languages that are sensitive to this. 
5. [jedi-vim](https://github.com/davidhalter/jedi-vim)
This plugin provides autocompletion for vim.
6. [pydoc.vim](https://github.com/fs111/pydoc.vim)
Python documentation. If you are python developer, you may want this plugin. 
7. [supertab](https://github.com/ervandew/supertab)

