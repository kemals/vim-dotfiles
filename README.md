# vim-dotfiles

### Prerequisites

1. Install vim 8 (required)
2. Install vim-plug, Minimalist Vim plugin manager that can be found here. It is awesome and it can be installed as easy as copying and pasting single curl command! 

### vim setup

1. Clone this repo:
'''
git clone https://github.com/kemals/vim-dotfiles
'''
2. Backup current .vimrc if there is one:
'''
cp ~/.vimrc ~/vimrc.bac
'''
3. Copy cloned config file as new .vimrc:
'''
cp vim-dotfiles/config/vimrc ~/.vimrc
'''
4. Open the newly copied file with vim:
'''
vim ~/.vimrc
'''
5. Once the vim opens the file, in Normal mode:
'''
:PlugInstall
'''
6. Plug will install all the modules listed in the .vimrc and once it completes just close the file:
'''
:q!
'''
7. Profit! 


