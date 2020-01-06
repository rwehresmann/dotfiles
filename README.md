# Personal dotfiles

## vimrc

1. Download [vim-plug](https://github.com/junegunn/vim-plug):

   ```shell
   curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
   ```

2. Symlink the dotfile `ln -s dotfiles/vim/vimrc .~/vimrc`;

3. Reload configuration `:source ~/.vimrc`;

4. Install plugins `:PlugInstall`.

The file describes CtrlP as a fuzzy finder, in order to use it got to [CtrlP](https://ctrlpvim.github.io/ctrlp.vim/#installation) and do the steps 1 and 3. In order make this finder work way faster, simply install [The Silver Searcher](https://github.com/ggreer/the_silver_searcher). 



## zshrc

1. Install [Oh My Zsh](https://ohmyz.sh/);
2. Symlink the dotfille `ln -s dotfiles/zsh/zshrc .~/zshrc`.

The install script from step 1 will already ask you to make zsh the default terminal. Even choosing yes, it may need necessary to restart your OS to apply the modification.