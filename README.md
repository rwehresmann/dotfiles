# Personal dotfiles

## vimrc

1. Download [vim-plug](https://github.com/junegunn/vim-plug):

   ```shell
   curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
   ```

2. Symlink the dotfile `ln -s dotfiles/vimrc .~/vimrc`;

3. Reload configuration `:source ~/.vimrc`;

4. Install plugins `:PlugInstall`.

In order to use the fuzzy finder, got to [ctrlp](https://ctrlpvim.github.io/ctrlp.vim/#installation) and do the step 1 and 3. 