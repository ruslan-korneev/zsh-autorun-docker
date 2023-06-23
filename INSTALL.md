# Installation

- [Oh My Zsh](#oh-my-zsh)

## Oh My Zsh

1. Clone this repository into $ZSH_CUSTOM/plugins (by default ~/.oh-my-zsh/custom/plugins)

```zsh
git clone https://github.com/ruslan-korneev/zsh-autorun-docker ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autorun-docker
```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside ~/.zshrc):

```zshrc
plugins=( 
    # other plugins...
    zsh-autorun-docker
)
```

3. Start a new terminal session or read `.zshrc`
```zsh
source ~/.zshrc
```
