# zen-dotfiles
A new, Zen (minimal) Zsh setup

## Install
### 1. Manually install the following in Zsh:
- [rust](https://rust-lang.org/tools/install/)
- [fzf](https://github.com/junegunn/fzf)
- [bd](https://github.com/vigneshwaranr/bd) (a powerul change-dir)
- [spaceship](https://github.com/spaceship-prompt/spaceship-prompt) for prompts
- [zsh auto completions](https://github.com/marlonrichert/zsh-autocomplete)
- [zsh auto suggestions](https://github.com/zsh-users/zsh-autosuggestions)
- [zsh syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)

### 2. Clone this repo into a dotfiles directory

### 3. Create symlinks
Save copies of the following files for backup if you have them:
- aliases
- functions
- .zshrc

Create their symlinks:
- `ln -sfv dotfiles/aliases aliases`
- `ln -sfv dotfiles/functions functions`
- `ln -sfv dotfiles/.zshrc .zshrc`

### 4. Reload your session
and you should get all the features and functionality sourced from this dotfiles repo.
