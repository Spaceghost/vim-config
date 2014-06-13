# How to use SpaceGhost's Brogramming vim configuration

## Always back up your vimrc, either with git or moving files.
mkdir ~/vim_backup && mv ~/.vim{,rc} ~/vim_backup/

## Clone your copy down
git clone git://github.com/Spaceghost/vim-config

cd vim-config && make install

vim +BundleInstall


