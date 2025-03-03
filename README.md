# install-software-cli

From a new laptop/pc, reinstall everything we need from cli with homebrew.

```
# homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# chrome
brew install --cask google-chrome

# anaconda
brew install --cask anaconda

# vscode
brew install --cask visual-studio-code

# pycharm
brew install --cask pycharm-ce

# sublime
brew install --cask sublime-text

# install gcp cli
brew install --cask google-cloud-sdk
gcould init

# k8s
brew install kubernetes-cli

# argo workflow
brew install argo

# git
brew install git

# karabiner-elements
brew install --cask karabiner-elements

# Notion
brew install --cask notion

# mendeley reference manager
brew install --cask mendeley-reference-manager

# mathpix snipping tool
brew install --cask mathpix-snipping-tool

# teams
brew install --cask microsoft-teams

# slack
brew install --cask slack

# list all installed packages
brew list
```

Git setup
```bash
# Checking for existing SSH keys
# https://docs.github.com/en/authentication/connecting-to-github-with-ssh/

# Adding a new SSH key to your GitHub account
# https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-accountgenerating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

# create ssh key
ssh-keygen -t ed25519 -C "xxxx@xxx.com.au"
cat /home/jupyter/.ssh/id_ed25519.pub

# add name and email
git config --global user.name "xxx"
git config --global user.email xxxx@xxxx.com.au

# add shortcut
git config --global alias.a "add ."
git config --global alias.s "status"
git config --global alias.cm "commit -m"

# check config
cat ~/.gitconfig
```
