# mac-dotfiles 🔧
.files for my daily driver ~~LinuxBook~~ MacBook
Mix of daily driver sensibility ⚙️
...with hacker nonsense ⁉️
![Neofetch](/MacNeofetchExample.png "Desktop")
## Overview

    Operating System : macOS 14
    Package Manager : Homebrew (brew)
    Terminal : Kitty; oh-my-zsh
    Text Editor : micro
    Web Browser : ungoogled-chromium
## Extensions
- [AltTab](https://github.com/lwouis/alt-tab-macos)
- [Marta](https://marta.sh/)
- Shortcuts?
## Installation
Warning: If you *really* want attempt to use MY dotfiles, you should at least fork the repository, review the dots, and remove things you don’t want or need. Don’t trust that random "people" on the internet have the same UI perferences as you. Use at your own risk!

- clone the repo 📝
`~$ git clone https://github.com/Mail222/mac-dotfiles`
- EDIT the dots ✂️
- copy files 📋
- enjoy!

Installing brew packages
`~$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` Needed for git and gitless
`~$ cd mac-dotfiles && chmod +x brew.sh && ./brew.sh`
`gitless install
~$ curl https://raw.githubusercontent.com/Mail222/mac-dotfiles/main/brew.sh | bash`
Installing neofetch config
`~$ mv ~/.config/neofetch/config.conf ~/.config/neofetch/config.conf.bak && cp mac-dotfiles/.config/neofetch/config.conf ~/.config/neofetch/config.conf
gitless install
~$ cd ~/.config/neofetch && cp config.conf config.conf.bak && curl https://raw.githubusercontent.com/Mail222/mac-dotfiles/main/.config/neofetch/config.conf > config.conf`
Installing zsh config (mgutz theme)
`~$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
`~$ mv ~/.zshrc ~/.zshrc.bak && cp mac-dotfiles/.zshrc ~/.zshrc`
Installing kitty config (WIP)
