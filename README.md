# Mac Setup powerlevel10k, zsh, neo-vim




# NeoVim

mkdir -p ~/.config/nvim/
cp config/nvim/init.vim ~/.config/nvim/init.vim
curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
