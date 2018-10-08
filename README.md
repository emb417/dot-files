# dot-files

## Environment Setup
1. Download / Install Xcode from App Store
1. Download / Install Google Chrome
1. Download / Install Slack
1. Configure Night Shift
1. Dowload Divvy Trial, Register with License
1. Copy PandaBar from USB Stick
1. Install Homebrew `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
1. Install Iterm2 `brew cask install iterm2`
1. Install zsh `brew install zsh`
1. Install Oh-My-Zsh `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
1. Close terminal and Open iterm
1. Install git `brew install git`
1. Configure git user name `git config --global user.name "Eric Brousseau"`
1. Configure git email `git config --global user.email "emb417@gmail.com"`
1. Configure git to use keychain `git config --global credential.helper osxkeychain`
1. Create .ssh Directory `mkdir ~/.ssh`
1. Copy SSH Keys from USB Stick to ~/.ssh
1. Change Permission Level `chmod 600 ~/.ssh/*`
1. Create github dir `mkdir ~/github`
1. Clone dot-files into github dir `git clone git@github.com:emb417/dot-files.git`
1. Copy files from github/dot-files to ~
1. Install vim `brew install vim`
1. Install Ultimate vim
   1. `git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime`
   1. `sh ~/.vim_runtime/install_awesome_vimrc.sh`
1. Install PowerLevel9K Theme `git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`
1. Clone and Install Roboto Mono Fonts from this repo: `git clone git@github.com:powerline/fonts.git`
1. Configure iterm profile>text Fonts and Non-ASCII Fonts to use Roboto Mono Medium
1. Clone Awesome Fonts `git clone git@github.com:gabrielelana/awesome-terminal-fonts.git`
1. Install Fonts using this guide: [https://github.com/gabrielelana/awesome-terminal-fonts/wiki/OS-X](https://github.com/gabrielelana/awesome-terminal-fonts/wiki/OS-X)
1. Install Editor of choice:
   1. Visual Studio Code `brew cask install visual-studio-code`
   1. Atom `brew cask install atom`
   1. Atom Plugins
      * Mini-Map
      * Split-Diff
      * Split-Diff-Minimap
      * linter
      * linter-babel
