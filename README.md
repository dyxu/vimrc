VIMRC
=============================================

Intro
---------------------------------------------
My personal vim configuration (.vimrc and .vim) for terminal.

Screenshot
---------------------------------------------
### Source Insight
![source insight](https://github.com/dyxu/vimrc/blob/master/screenshot/source\ insight.png)

### AutoComplete
![Autocomplete](https://github.com/dyxu/vimrc/blob/master/screenshot/YCM.png)


Installation
--------------------------------------------
### Ubuntu Linux Installation
This vim configuration includes a lot of great plugins, configurations and color schemes that
make VIM a lot better. To install it simply do following:

    cd ~
    git clone https://github.com/dyxu/vimrc.git

You'd better backup your vim configuration.

    mv .vim .vim.bak
    mv .vimrc .vimrc.bak

Then

    cp ./vim/.vim ./
    cp ./vim/.vimrc .vimrc

The vimrc is already setup, have fun!

### Errors In Installation
#### ctags or cscope
ctags and cscope should be installed for some plugins (SrcExpl and ccvext). so install them:

    sudo apt-get install ctags
    sudo apt-get install cscope

#### YouCompleteMe
you need reinstall YouCompleteMe for your local environment.(more details in [YouCompleteMe](https://github.com/Valloric/YouCompleteMe))

Plugins
--------------------------------------------
These plugins are installed in my configurations:

1. [vundle](https://github.com/gmarik/Vundle)
2. [a.vim](https://github.com/vim-scripts/a.vim)
3. [Align](https://github.com/vim-scripts/Align)
4. [auto-pairs](https://github.com/jiangmiao/auto-pairs)
5. [bufexplorer](https://github.com/vim-scripts/bufexplorer.zip)
6. [ccvext](https://github.com/vim-scripts/ccvext.vim)
7. [cSyntaxAfter](https://github.com/vim-scripts/cSyntaxAfter)
8. [indentLine](https://github.com/Yggdroot/indentLine)
9. [Mark--Karkat](https://github.com/vim-scripts/Mark--Karkat)
10. [neocomplcache](https://github.com/Shougo/neocomplcache.vim)
11. [nerdcommenter](https://github.com/scrooloose/nerdcommenter)
12. [nerdtree](https://github.com/scrooloose/nerdtree)
13. [vim-powerline](https://github.com/Lokaltog/vim-powerline)
14. [repeat](://github.com/vim-scripts/repeat.vim)
15. [snipmate](https://github.com/msanders/snipmate.vim)
16. [SrcExpl](https://github.com/wesleyche/SrcExpl)
17. [tagbar](https://github.com/majutsushi/tagbar)
18. [taglist](https://github.com/vim-scripts/TagList.vim)
19. [TxtBrowser](https://github.com/vim-scripts/TxtBrowser)
20. [vim-fugitive](https://github.com/vim-scripts/vim-fugitive)
21. [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)

more details see [.vimrc](https://github.com/dyxu/vimrc/blob/master/.vimrc)
