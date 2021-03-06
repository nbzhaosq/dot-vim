nbzhaosq's vim configuration
============================

##useage
git clone https://github.com/nbzhaosq/dot-vim.git .vim

cd .vim

git submodule update --init --recursive
- the third command will automatically download Vundle.vim as submodule

(on *nix, you can ln -s `pwd`/.vim/dot-vimrc .vimrc; on windows, you should copy the dot-vimrc file as .vimrc manually)
(on windows, clone the project to C:/User/{your username}/ and rename folder to ".vim" and copy the dot-vimrc file to C:/User/{your username}/.vimrc,
remember you may need git command in your Path )

open your favorite vim editor, enter the follow: ":PluginInstall"


## main plugins
- Vundle
- YouCompleteMe (YCM)  (this feature need cmake and gcc)
- ultisnips
- nerdtree
- tagbar
- poweline


## C/C++
work with YCM
#### requirements :
YCM-PATH/install.sh --clang-completer

## Python
work with jedi
#### requirements :
pip install jedi

## Ruby
use [vim-ruby](https://github.com/vim-ruby/vim-ruby)
work with jedi
#### requirements :
pip install jedi

## Golang
work with vim-go
#### requirements :
go get -u github.com/nsf/gocode

## Nodejs
work with ternjs_for_vim

## Java
javacomplete
#### requirements :
jdk version > 1.1

## Clojure
work with lein repl
#### requirements :
lein

## Notification
vim needs python-plugin on while compiled
some linux dist's default vim not compiled with python-plugin on

on Ubuntu, the vim can be installed directly use "sudo apt-get install vim"

on openSUSE, the vim needs to be compiled manully
