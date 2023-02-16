### zsh dot file
- based on [oh my zsh](https://ohmyz.sh)

#### plugins
  - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
  - [syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
  - [command-line fuzzy finder](https://github.com/junegunn/fzf)
    - modify `.fzf.zsh` file after moving `.fzf` directory
    ```
    PATH="${PATH:+${PATH}:}/Users/jake-imac/.config/zsh/.fzf/bin"
    ```

#### configuration
- set ZDOTDIR in ~/.zshenv file like this
  ```sh
  export ZDOTDIR=$HOME/.config/zsh
  ```

- make directory ~/.cache/zsh for history

- put global `.gitconfig` file into `.config/git` as `config`

- change shortcut
  - input source as option + space
  - screenshot and recording options as left control + shift + command + 5

- create `.vimrc` for `.viminfo` file
  - `set viminfo+=n~/.config/vim/.viminfo`

