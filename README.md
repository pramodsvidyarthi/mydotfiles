# Installation:

    git clone https://github.com/pramodsvidyarthi/mydotfiles.git ~/.vim
	
## For Windows users using Gvim

   Clone the repo into the Vimfiles folder under "Program Files/Vim"

# Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc
	
#For Windows users using Gvim

   cd Vim/vimfiles
   MKLINK -H /Program Files/Vim/.vimrc /Program Files/Vim/vimfiles/.vimrc
   MKLINK -H /Program Files/Vim/.gvimrc /Program Files/Vim/vimfiles/.gvimrc


Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update

