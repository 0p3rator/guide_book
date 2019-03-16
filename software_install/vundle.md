# vundle

1. git and curl is required
```
sudo apt-get install git curl 
```

2. init directory
```
mkdir -p ~/.vim/autoload ~/.vim/bundle
```

3. clone vundle code from git
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

4. add following contents into `.vimrc` 
```
set nocompatible              
filetype off                 

set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

Plugin 'VundleVim/Vundle.vim'

call vundle#end()            
filetype plugin indent on   
```
