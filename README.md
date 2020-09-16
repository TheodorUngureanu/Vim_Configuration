# Vim_Configuration

### Install Plugin Installer for vim
```
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
  https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

### To install grubbox color scheme add this in .vimrc file
```
call plug#begin()
Plug 'morhetz/gruvbox'
call plug#end()
```

### Enter vim and write ```:PlugInstall```

### Copy the gruvbox.vm color file in the right path:
#### Link for theme: https://vimawesome.com/plugin/gruvbox
```
cp colors/gruvbox.vim .vim/
```
