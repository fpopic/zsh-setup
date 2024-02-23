# zsh-setup

- install `iterm2` https://iterm2.com/
- install `brew` https://brew.sh/
- install `oh-my-zsh` https://ohmyz.sh/#install
- change theme to `half-life-fpopic`
  - https://www.linkedin.com/pulse/making-custom-zsh-theme-fun-aesthetic-md-mohibur-rahman/
- install plugins
  - how to enable fish-like features in zsh
    ```shell
    1. Install oh-my-zsh
    sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    
    2. Clone necessary plugins.
    git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
    git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    
    3. Add plugins to ~/.zshrc as
    plugins = ( [plugins...] zsh-autosuggestions zsh-history-substring-search zsh-syntax-highlighting)
    Note: make sure zsh-syntax-highlighting is the last one in the above list.
    
    4. Fix background theme issues (Not necessary depends on your theme)
    ZSH_AUTOSUGGEST_HIGHLIGHT_STYLE='fg=white'
    
    5. Restart zsh
    source ~/.zshrc
    ```
  - https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins
  - https://jonas.verhoelen.de/productivity/migrate-fish-to-zsh/

