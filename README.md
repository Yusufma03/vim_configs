# Vim Configs

To use the configs, download the ``.vimrc`` and ``.vimrc.bundles`` files, and replace the original configs with the new ones.

Next, install Vundle and corresponding plugins:
```
$ git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
$ vim
$ :BundleInstall
```

The next step is to compile ``YouCompleteMe``, 
```
$ cd .vim/bundle/YouCompleteMe/ && python install.py
```
You will need ``cmake`` for compilation.

In addition, the customized python indentation file should be setup as
```
$ mkdir ~/.vim/indent
$ cp python.vim ~/.vim/indent/python.vim
```

