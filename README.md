# How to use SpaceGhost's Brogramming vim configuration

mkdir ~/vim_backup && mv ~/.vim{,rc} ~/vim_backup/

git clone git://github.com/Spaceghost/vim-config

cd vim-config && make install

git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

vim +BundleInstall

Note: LustyJuggler requires vim-ruby installed.


