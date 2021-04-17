# Dotfiles (WIP)

[Instructions for setting up your own dotfiles repository](https://antelo.medium.com/how-to-manage-your-dotfiles-with-git-f7aeed8adf8b)

This repository is untested. I plan on testing when I have a new device and need to use these dotfiles. Nevertheless, I have made it public to share my dotfiles.

## The below are untested

### To set up a computer from scratch

- Clone the repository

```
git clone --bare https://github.com/mxchaeltrxn/dotfiles.git ~/.dotfiles
```

- Checkout the contents of `.dotfiles` to your HOME directory (`~`).
  _I'm not sure why this line is needed but it was in the instructions in the 'Instructions for setting up your own dotfiles repository' url I linked above._

```
dotfiles checkout
```

- Run installation script

```
sh first-time-install.sh
```

### To set up continuous updates

Set up a cronjob to keep pulling the data down?
Write a script to install any new vs code extensions.
