# MacOS
## Oh my zsh!
- [ohmyzsh](https://ohmyz.sh/)
```
# ohmyzsh
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# pure theme
$ mkdir -p "$HOME/.zsh"
$ git clone https://github.com/sindresorhus/pure.git "$HOME/.zsh/pure"

# syntax highlighting
$ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# fzf
$ brew install fzf
```

## Packages
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- [git-delta](https://github.com/dandavison/delta)
- [bat](https://github.com/sharkdp/bat)
- [fnm](https://github.com/Schniz/fnm)

```
$ brew install ripgrep git-delta bat fnm
```

### Bat post installation
- Copy `dot-files/.config/bat` into `~/.config/bat`.
- Run `bat cache --build`.

## Font
- [Hack font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hack)
```
$ brew tap homebrew/cask-fonts && brew install --cask font-hack-nerd-font
```

brew install --cask dbeaver-community
