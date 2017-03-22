# vimConfig
config for c family programmer using vim

## Usage
1. place .vimrc in ~/ directory.
2. Set up Vundle:

   `$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
3. Install plugins:
* Open vim.
* Type: `:PluginInstall`
* Be patient. YouCompleteMe is large.
4. Setup semantic support for C-family languages: (taken from YouCompleteMe/README.md)
* Install development tools and CMake: `sudo apt-get install build-essential cmake`
* Make sure you have Python headers installed: `sudo apt-get install python-dev
python3-dev`.
* Compile YCM:

    cd ~/.vim/bundle/YouCompleteMe
    ./install.py --clang-completer
* Place .ycm_global_extra_conf.py in `~/.vim`
