# TODO.md

***

Install bash-completions

```bash
# install newer (i.e. 5.x ) version of bash and bash-completion
#brew install bash bash-completion@2

# . . . or install bash-completion for older bash (i.e. 3.2.X) that Apple ships
brew install bash-completion

# configure bash to use completions
cat << EOT >> ~/.bash_profile
[[ -r "$(brew --prefix)/etc/profile.d/bash_completion.sh" ]] && . "$(brew --prefix)/etc/profile.d/bash_completion.sh"
EOT

# enable docker completions
mkdir -p ~/.local/share/bash-completion/completions
docker completion bash > ~/.local/share/bash-completion/completions/docker
```

***

Install iterm 2 and load custom profiles

```bash
brew install iterm2
cp $DOTFILES_REPO/.iterm/profiles.json ~/Library/Application Support/iTerm2/DynamicProfiles
```

***

- [Beautify your iTerm2 and prompt | by Steven Chim | Medium](https://medium.com/airfrance-klm/beautify-your-iterm2-and-prompt-40f148761a49)

***

Grab iterm colour schemes

- [Iterm Themes - Color Schemes and Themes for Iterm2](https://iterm2colorschemes.com/)
- [mbadolato/iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes)

```bash
gh repo clone mbadolato/iTerm2-Color-Schemes
git clone git@github.com:mbadolato/iTerm2-Color-Schemes.git
git clone https://github.com/mbadolato/iTerm2-Color-Schemes.git
```

***

Grab nord colours and themes

- [Nord](https://www.nordtheme.com/)
- [Nord](https://github.com/nordtheme)
- [nordtheme/putty](https://github.com/nordtheme/putty)
- [nordtheme/assets](https://github.com/nordtheme/assets)
- [nordtheme/xcode](https://github.com/nordtheme/xcode)
- [nordtheme/web](https://github.com/nordtheme/web)
- [nordtheme/terminal-app](https://github.com/nordtheme/terminal-app)
- [nordtheme/slack](https://github.com/nordtheme/slack)
- [nordtheme/hyper](https://github.com/nordtheme/hyper)
- [nordtheme/highlightjs](https://github.com/nordtheme/highlightjs)
- [nordtheme/iterm2](https://github.com/nordtheme/iterm2)
- [nordtheme/dircolors](https://github.com/nordtheme/dircolors)
- [nordtheme/jetbrains](https://github.com/nordtheme/jetbrains)
- [nordtheme/tmux](https://github.com/nordtheme/tmux)
- [nordtheme/vim](https://github.com/nordtheme/vim)
- [nordtheme/alacritty](https://github.com/nordtheme/alacritty)
- [nordtheme/visual-studio-code](https://github.com/nordtheme/visual-studio-code)

- [grumpydumpty/omamac](https://github.com/grumpydumpty/omamac)
- [grumpydumpty/omadots](https://github.com/grumpydumpty/omadots)
- [grumpydumpty/omarchy](https://github.com/grumpydumpty/omarchy/blob/master/config/alacritty/alacritty.toml)
- [Omarchy Themes - A comprehensive collection of themes for Omarchy](https://omarchythemes.com/)

- [Midnight Commander - Skin Editor](https://skins.midnight-commander.org/)
- [MidnightCommander/skins: Midnight Commander Skin Editor](https://github.com/MidnightCommander/skins/tree/master)

- [mbadolato/iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes/)

- [Hyper Store - hyper-material-theme](https://hyper.is/store/hyper-material-theme)
- [Hyper Store - verminal](https://hyper.is/store/verminal)

***

Install iA Writer fonts
brew install font-ia-writer-mono font-ia-writer-duo font-ia-writer-quattro

***
_Last updated on: 2026/05/17_
