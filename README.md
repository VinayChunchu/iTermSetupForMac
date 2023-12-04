# iTermSetupForMac
Set of instructions to configure iterm console for a developer

# Install Iterm from official website
https://iterm2.com/downloads/stable/latest

# Install oh my zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/vinaychunchu/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

# Install powerlevel10k theme for oh my zsh
brew install powerlevel10k
echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc

# Hint: Type p10k configure to access the built-in configuration wizard right from your terminal.

# Install Bat (Alternate to cat command)
brew install bat

# Install exa (Alternate to ls command)
brew install exa
