# astrovim setup


1) Download [iTerm2](https://iterm2.com/)
2) Install [Homebrew](https://brew.sh/)
    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
3) Install [NeoVim](https://neovim.io/)
    ```
    brew install neovim
    ```
4) Download [NerdFonts](https://www.nerdfonts.com/) (FiraCode Nerd Font)
5) [AstroVim](https://astronvim.github.io/) setup
    - [ripgrep](https://github.com/BurntSushi/ripgrep) - live grep telescope search (<leader>fw)
    - [lazygit](https://github.com/jesseduffield/lazygit) - git ui toggle terminal (<leader>tl or <leader>gg)
    - [Node](https://nodejs.org/en/) - node repl toggle terminal (<leader>tn)
    - Installation
        - Make a backup of your current nvim folder
            ```
            mv ~/.config/nvim ~/.config/nvim.bak
            ```
        - Clean neovim folders (Optional but recommended)
            ```
            mv ~/.local/share/nvim ~/.local/share/nvim.bak
            mv ~/.local/state/nvim ~/.local/state/nvim.bak
            mv ~/.cache/nvim ~/.cache/nvim.bak
            ```
        - Clone the repository
            ```
            git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
            nvim
            ```    
