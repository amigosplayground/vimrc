vimrc
=====

My .vimrc file.

sudo apt-get build-dep vim

git clone https://github.com/vim/vim.git
cd vim


./configure --with-features=huge --enable-multibyte --enable-python3interp --with-python3-config-dir=/usr/lib/python3.8/config-3.8-x86_64-linux-gnu --enable-rubyinterp --enable-perlinterp --enable-luainterp --enable-gui=gtk2 --enable-cscope --prefix=/usr/local

sudo make install

which vim

vim --version

sudo update-alternatives --install /usr/bin/editor editor /usr/local/bin/vim 1
sudo update-alternatives --set editor /usr/local/bin/vim

