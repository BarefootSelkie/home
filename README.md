# Selkie Terminal

## Debian

Install zsh and make it the default terminal

```
sudo apt install zsh
chsh -s /bin/zsh
```

Reloading .zshrc

```source $HOME/.zshrc```

Autocomplete install

```git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions```

Add the following to your .zshrc:

```source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh```
