# Setup

## zsh

1. Set up [zsh]

2. Install [oh-my-zsh]

```zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

- Install Plugins

  - [zsh-autosuggestions]

    ```zsh
    git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins
    ```

  - [zsh-syntax-highlighting]

    ```zsh
    git clone https://github.com/zsh-users/zsh-syntax-highlighting ~/.oh-my-zsh/custom/plugins
    ```

## vim

My vim configuration

### Quick Start Install

- Set up [Plug]:

  ```zsh
  curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
  ```

- Install Plugins:

  Launch `vim` and run `:PlugInstall`

  To install from command line: `vim +PlugInstall +qall`

- Install [nerdfonts]:

download and install fronts

- Set up [Markdown]:

```zsh
[sudo] npm install -g instant-markdown-d
```

### Tips

- You can use `Shift` + `i` to see hidden files [NerdTree]

[zsh]: https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH
[oh-my-zsh]: https://github.com/ohmyzsh/ohmyzsh
[zsh-autosuggestions]: https://github.com/zsh-users/zsh-autosuggestions
[zsh-syntax-highlighting]: https://github.com/zsh-users/zsh-syntax-highlighting
[plug]: https://github.com/junegunn/vim-plug
[vim]: https://www.vim.org/
[nerdfonts]: https://www.nerdfonts.com/font-downloads
[markdown]: https://github.com/suan/vim-instant-markdown
[nerdtree]: https://github.com/preservim/nerdtree
