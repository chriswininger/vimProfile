### [Vim](http://www.vim.org/)

#### Install

These are the default instructions using Vim 8's `|packages|` feature.

1. Create theme folder (in case you don't have yet):

```
mkdir -p ~/.vim/pack/themes/start
```

2. Copy the `vim` folder and rename to "dracula_pro":

```
cp -r vim ~/.vim/pack/themes/start/dracula_pro
```

#### Activate

1. Create configuration file (in case you don't have yet):

```
vim ~/.vimrc
```

2. Edit the `~/.vimrc` file with the following content:

```
packadd! dracula_pro

syntax enable

" You need a 256-color or truecolor terminal
" and you may want one that supports xterm sequences for :terminal

colorscheme dracula_pro
```