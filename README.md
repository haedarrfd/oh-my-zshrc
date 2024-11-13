# Oh My Zshrc

> [!NOTE]
> This `.zshrc` configuration is tailored for my UNIX system and may require adjustments on other systems. So if you encounter any issues, you need to make your own setup.

> [!WARNING]
> This repository will not receive any further updates, as my **dotfiles** is already set up for general use.  For future improvements, please feel free to see my **dotfiles** repo [here](https://github.com/haedarrfd/dotfiles.git).

## Introduction

oh-my-zshrc is my setup configuration for the [Z shell](https://en.wikipedia.org/wiki/Z_shell) (zsh), designed to enhance my productivity while code and improving my knowledge of scripting.

## ⚡️ Requirements

* **Zsh** >= 5.9
* By default, UNIX system use **bash**. You need to [change the default bash to zsh](https://swaroop-m.medium.com/how-to-change-the-default-bash-shell-to-zsh-on-linux-de7f80839b7a).

## 📦 Installation

Follow these command to install this setup:

```shell
mv ~/.zshrc ~/.zshrc.bak # If you are using bash before, just change .zshrc to .bashrc
git clone https://github.com/haedarrfd/oh-my-zshrc .
source ~/.zshrc
```

After that, your terminal will be automatically install all plugins that exists in the `.zshrc` file.

## ✨ Plugins

* Zinit as the Zshell plugin manager that will install all plugins that are available. See [documentation](https://github.com/zdharma-continuum/zinit)
* Zsh syntax highlighting for easier readability. See [documentation](https://github.com/zsh-users/zsh-syntax-highlighting)
* Zsh completions. See [documentation](https://github.com/zsh-users/zsh-completions)
* Zsh autosuggestions as you type based on history. See [documentation](https://github.com/zsh-users/zsh-autosuggestions)

## 🎨 Themes

I use [Starhip](https://starship.rs/) for prompt with custom themes. You can use another themes for example [Powerlevel10k](https://github.com/romkatv/powerlevel10k). If you'd still like to use starhip, I'll leave my repo where you can check on my starship setup [here](https://github.com/haedarrfd/oh-my-starship.git).
