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
- [nordtheme/putty: An arctic, north-bluish clean and elegant PuTTY color theme.](https://github.com/nordtheme/putty)
- [nordtheme/assets: Assets for the Nord project.](https://github.com/nordtheme/assets)
- [nordtheme/xcode: An arctic, north-bluish clean and elegant Xcode color theme.](https://github.com/nordtheme/xcode)
- [nordtheme/web: The official Nord website and documentation](https://github.com/nordtheme/web)
- [nordtheme/terminal-app: An arctic, north-bluish clean and elegant Terminal.app color theme.](https://github.com/nordtheme/terminal-app)
- [nordtheme/slack: An arctic, north-bluish clean and elegant Slack theme.](https://github.com/nordtheme/slack)
- [nordtheme/hyper: An arctic, north-bluish clean and elegant Hyper theme plugin.](https://github.com/nordtheme/hyper)
- [nordtheme/highlightjs: An arctic, north-bluish clean and elegant highlight.js theme.](https://github.com/nordtheme/highlightjs)
- [nordtheme/iterm2: An arctic, north-bluish clean and elegant iTerm2 color scheme.](https://github.com/nordtheme/iterm2)
- [nordtheme/dircolors: An arctic, north-bluish clean and elegant dircolors theme.](https://github.com/nordtheme/dircolors)
- [nordtheme/jetbrains: An arctic, north-bluish clean and elegant JetBrains IDE UI and editor color theme.](https://github.com/nordtheme/jetbrains)
- [nordtheme/tmux: An arctic, north-bluish clean and elegant tmux color theme.](https://github.com/nordtheme/tmux)
- [nordtheme/vim: An arctic, north-bluish clean and elegant Vim theme.](https://github.com/nordtheme/vim)
- [nordtheme/alacritty: An arctic, north-bluish clean and elegant Alacritty color scheme.](https://github.com/nordtheme/alacritty)
- [nordtheme/visual-studio-code: An arctic, north-bluish clean and elegant Visual Studio Code theme.](https://github.com/nordtheme/visual-studio-code)

- [grumpydumpty/omamac](https://github.com/grumpydumpty/omamac)
- [grumpydumpty/omadots](https://github.com/grumpydumpty/omadots)
- [grumpydumpty/omarchy](https://github.com/grumpydumpty/omarchy/blob/master/config/alacritty/alacritty.toml)
- [Omarchy Themes - A comprehensive collection of themes for Omarchy](https://omarchythemes.com/)

- [Midnight Commander - Skin Editor](https://skins.midnight-commander.org/)
- [MidnightCommander/skins: Midnight Commander Skin Editor](https://github.com/MidnightCommander/skins/tree/master)

- [iTerm2-Color-Schemes/dynamic-colors/Nord.sh at master · mbadolato/iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/dynamic-colors/Nord.sh)

- [Hyper Store - hyper-material-theme](https://hyper.is/store/hyper-material-theme)
- [Hyper Store - verminal](https://hyper.is/store/verminal)

***

Install iA Writer fonts
brew install font-ia-writer-mono font-ia-writer-duo font-ia-writer-quattro

***
_Last updated on: 2026/05/17_
