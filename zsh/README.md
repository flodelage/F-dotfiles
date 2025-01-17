# Zsh

Package tree:

zsh
├── .oh_my.zsh
├── .p10k.zsh
├── .zsh
│   ├── aliases.zsh
│   ├── config.zsh
│   ├── dircolors.256dark
│   └── functions.zsh
├── .zshenv
├── .zshrc
└── README.md

1 directory, 9 files

---

This package [loads Oh-My-Zsh](https://github.com/Kraymer/F-dotfiles/blob/master/zsh/.oh_my.zsh) and activate powerlevel10k theme.
It defines some [aliases](https://github.com/Kraymer/F-dotfiles/blob/master/zsh/.zsh/aliases.zsh) that adds sane options to core shell functions and GNU utilities.

### Customization

Others packages define environment variables or functions by writing shell files into `~/.zsh`.

`~/.zsshenv` sources all **.zshenv* files present in `~/.zsh` subfolders at zsh startup, and `~/.zshrc` do the same with **.zsh* files.

### Requirements

- `oh-my-zsh` <<https://github.com/robbyrussell/oh-my-zsh>>
- `powerlevel10k` <<https://github.com/romkatv/powerlevel10k/>>
- custom Oh-my-zsh plugins listed at the end of https://raw.githubusercontent.com/Kraymer/F-dotfiles/master/zsh/.oh_my.zsh
