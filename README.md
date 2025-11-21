# dotfiles

Save dotfiles/local configuration.

## Onboarding

```bash
git clone git@github.com:jamestrousdale/dotfiles.git ~/dotfiles

ln -s ~/dotfiles/bash/bashrc ~/.bashrc
ln -s ~/dotfiles/bash/bash_profile ~/.bash_profile
mkdir -p ~/.config
ln -s ~/dotfiles/config/starship.toml ~/.config/starship.toml
```

## macOS setup

```bash
brew install bash
brew install starship
brew install mise
```
