# zer0-x's public dotfiles
> Managed with [chezmoi](https://www.chezmoi.io/)

Those config files and dependencies represents my Personalized Development Environment.

## Dependencies

### GUI Applications
- [kitty](https://archlinux.org/packages/community/x86_64/kitty/) <sup>`Terminal emulator`</sup>
- [sqlitebrowser](https://archlinux.org/packages/community/x86_64/sqlitebrowser/)
- [ghostwriter](https://archlinux.org/packages/community/x86_64/ghostwriter/) <sup>`For writing in Arabic smoothly`</sup>
- [mpv](https://archlinux.org/packages/community/x86_64/mpv/) <sup>`Media player`</sup>
- [feh](https://archlinux.org/packages/extra/x86_64/feh/) <sup>`Image viewer`</sup>
- [qalculate-qt](https://archlinux.org/packages/extra/x86_64/qalculate-qt/)
- [zathura](https://archlinux.org/packages/community/x86_64/zathura/) <sup>`Document Viewer`</sup>
    - [zathura-pdf-mupdf](https://archlinux.org/packages/community/x86_64/zathura-pdf-mupdf/)

### Desktop Environment
- [rofi](https://archlinux.org/packages/community/x86_64/rofi/) <sup>`Launcher`</sup>
    - [rofi-calc](https://archlinux.org/packages/community/x86_64/rofi-calc/)
    - [rofi-emoji](https://archlinux.org/packages/community/x86_64/rofi-emoji/)
    - [foxmarks](https://aur.archlinux.org/packages/foxmarks)

### Fonts
- [JetBrainsMono Nerd](https://aur.archlinux.org/packages/nerd-fonts-jetbrains-mono)

### CLI Applications/Tools
- [git](https://archlinux.org/packages/extra/x86_64/git/)
- [python-livereload](https://archlinux.org/packages/community/any/python-livereload/)
- [libqalculate](https://archlinux.org/packages/extra/x86_64/libqalculate/)

### CLI Utilities
- [bat](https://archlinux.org/packages/community/x86_64/bat/)
- [fd](https://archlinux.org/packages/community/x86_64/fd/) <sup>`find alternative`</sup>
- [zoxide](https://archlinux.org/packages/community/x86_64/zoxide/) <sup>`cd alternative`</sup>
- [exa](https://archlinux.org/packages/community/x86_64/exa/) <sup>`ls alternative`</sup>
- [fzf](https://archlinux.org/packages/community/x86_64/fzf/) <sup>`fuzzy finder`</sup>

### Zsh <sup>`Shell`</sup>
- [zsh](https://archlinux.org/packages/extra/x86_64/zsh/)
    - [zsh-autosuggestions](https://archlinux.org/packages/community/any/zsh-autosuggestions/)
    - [zsh-completions](https://archlinux.org/packages/community/any/zsh-completions/)
    - [zsh-history-substring-search](https://archlinux.org/packages/community/any/zsh-history-substring-search/)
    - [zsh-syntax-highlighting](https://archlinux.org/packages/community/any/zsh-syntax-highlighting/)
    - [zsh-theme-powerlevel10k](https://archlinux.org/packages/community/x86_64/zsh-theme-powerlevel10k/)


### NeoVim <sup>`Text Editor`</sup>
- [neovim](https://archlinux.org/packages/community/x86_64/neovim/)
- [nvim packer](https://aur.archlinux.org/packages/nvim-packer-git)

After installing packer, you need to install the plugins for neovim by running:
```
:PackerSync
```

#### sup-dependencies <sup>`Required by NeoVim plugins`</sup>
- [ripgrep](https://archlinux.org/packages/community/x86_64/ripgrep/)

### Language Servers
- [rust-analyzer](https://archlinux.org/packages/community/x86_64/rust-analyzer/) <sup>`Rust`</sup>
- [jedi-language-server](https://archlinux.org/packages/community/any/jedi-language-server/) <sup>`Python`</sup>
- [texlab](https://archlinux.org/packages/community/x86_64/texlab/) <sup>`LaTex`</sup>
- [typescript-language-server](https://archlinux.org/packages/community/any/typescript-language-server/) <sup>`JavaScript/TypeScript`</sup>
- [vscode-css-languageserver](https://archlinux.org/packages/community/any/vscode-css-languageserver/) <sup>`CSS`</sup>
- [vscode-html-languageserver](https://archlinux.org/packages/community/any/vscode-html-languageserver/) <sup>`HTML`</sup>
- [lua-language-server](https://archlinux.org/packages/community/x86_64/lua-language-server/) <sup>`Lua`</sup>

### Linters
- [flawfinder](https://archlinux.org/packages/community/any/flawfinder/) <sup>`C/C++`</sup>
- [mypy](https://archlinux.org/packages/community/any/mypy/) <sup>`Python`</sup>
- [flake8](https://archlinux.org/packages/community/any/flake8/) <sup>`Python`</sup>
    - [pep8-naming](https://aur.archlinux.org/packages/python-pep8-naming)
    - [flake8-builtins](https://aur.archlinux.org/packages/python-flake8-builtins)
    - [flake8-comprehensions](https://aur.archlinux.org/packages/python-flake8-comprehensions)
    - [flake8-bugbear](https://aur.archlinux.org/packages/python-flake8-bugbear)
- [python-pydocstyle](https://archlinux.org/packages/community/any/python-pydocstyle/) <sup>`Python`</sup>
- [Bandit](https://archlinux.org/packages/community/any/bandit/) <sup>`Python`</sup>
- [selene-linter](https://archlinux.org/packages/community/x86_64/selene-linter/) <sup>`Lua`</sup>
- [eslint](https://archlinux.org/packages/community/any/eslint/) <sup>`JavaScript/TypeScript`</sup>
- [stylelint](https://archlinux.org/packages/community/any/stylelint/) <sup>`CSS`</sup>
- [tidy](https://archlinux.org/packages/extra/x86_64/tidy/) <sup>`HTML`</sup>

### Formatters
- [black](https://archlinux.org/packages/community/any/python-black/) <sup>`Python`</sup>

### Programming Languages Tools/Compilers/Interpreters
#### Rust
- [rustup](https://archlinux.org/packages/community/x86_64/rustup/)

After installing it you need to run:
```shell
rustup default stable
```

> **Note** It includes most the tools used for the Rust language.

#### C/C++
- [clang](https://archlinux.org/packages/extra/x86_64/clang/)

#### Python
- [python](https://archlinux.org/packages/core/x86_64/python/)

#### LaTex
- [texlive-most](https://archlinux.org/groups/x86_64/texlive-most/)
- [texlive-langextra](https://archlinux.org/packages/extra/any/texlive-langextra/)
- [texlive-fontsextra](https://archlinux.org/packages/extra/any/texlive-fontsextra/)

## Arch linux Installation
In your shell, run:
```shell
sudo pacman -S --needed ripgrep fd clang rustup jedi-language-server texlab typescript-language-server vscode-css-languageserver vscode-html-languageserver lua-language-server flawfinder mypy flake8 python-pydocstyle selene-linter eslint stylelint tidy texlive-most texlive-langextra texlive-fontsextra ghostwriter kitty mpv feh zsh bandit bat qalculate-qt libqalculate rust-analyzer python-black exa zoxide zsh-autosuggestions zsh-completions zsh-history-substring-search zsh-syntax-highlighting zsh-theme-powerlevel10k zathura-pdf-mupdf zathura rofi rofi-calc rofi-emoji

yay -Sa nvim-packer-git python-flake8-builtins python-flake8-bugbear python-flake8-comprehensions python-pep8-naming nerd-fonts-jetbrains-mono foxmarks

rustup default stable
```

Then inside neovim, run:
```
:PackerSync
```

## Screen Shots

### Kitty & zsh <sup>[~/.config/kitty](https://github.com/zer0-x/dotfiles/tree/main/dot_config/kitty) | [~/.zshrc](https://github.com/zer0-x/dotfiles/blob/main/dot_zshrc)</sup>
<img width=500px src="" alt="Screenshot for kitty and zsh">

### neovim <sup>[~/.config/nvim/](https://github.com/zer0-x/dotfiles/tree/main/dot_config/nvim)</sup>
<img width=500px src="" alt="Screenshot for neovim">

### [ghostwriter](https://wereturtle.github.io/ghostwriter/) <sup>[~/.config/ghostwriter](https://github.com/zer0-x/dotfiles/tree/main/dot_config/ghostwriter)</sup>
<img width=500px src="" alt="Screenshot for ghostwriter">
