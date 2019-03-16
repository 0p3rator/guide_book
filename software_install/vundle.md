# vundle

## About vundle

**Vundle** is short for _Vim Vundle_, it is a plugin mananger for **vim**
**Vundle** allows you to
* In file `.vimrc`, follow and [manage](https://github.com/VundleVim/Vundle.vim/blob/v0.10.2/doc/vundle.txt#L126-L233) plugins
* [install](https://github.com/VundleVim/Vundle.vim/blob/v0.10.2/doc/vundle.txt#L234-L254) specific type plugins(a.k.a. scripts/bundle)
* [upgrade](https://github.com/VundleVim/Vundle.vim/blob/v0.10.2/doc/vundle.txt#L255-L265) specific type plugins
* [search](https://github.com/VundleVim/Vundle.vim/blob/v0.10.2/doc/vundle.txt#L266-L295) [Vim scripts](http://vim-scripts.org/vim/scripts.html) plugins by plugin name
* [remove](https://github.com/VundleVim/Vundle.vim/blob/v0.10.2/doc/vundle.txt#L303-L318) plugins unused


## Quickly start

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
```vim
set nocompatible              
filetype off                 

set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

Plugin 'VundleVim/Vundle.vim'

call vundle#end()            
filetype plugin indent on   
```

5. install plugin
   run `vim` then run `:PluginInstall`
   or directly install by command `vim +PluginInstall +qall`
