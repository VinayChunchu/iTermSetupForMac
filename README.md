# iTermSetupForMac
Set of instructions to configure iterm console for a developer

### Install Iterm from official website

> [!NOTE]
> Iterm2 is a good alternative to a built-in Mac terminal.

https://iterm2.com/downloads/stable/latest

### Install oh my zsh
> [!NOTE]
> Use the following command to install ohmyzsh into iterm2. This will add plugins and themes to your terminal.

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

### Install homebrew
> [!NOTE]
> Use the following command to install homebrew. This will add a package manager which will help install more applications and tools on your Mac. You will be using the brew command very often.

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

> [!NOTE]
> Run the steps specified at the end of the output for the previous command. These steps will add the homebrew to your profile so that you can use it in any path of your Mac.
> My output shows the below commands to run. These might be different for you.

`(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/vinaychunchu/.zprofile`

`eval "$(/opt/homebrew/bin/brew shellenv)"`

### Install powerlevel10k theme for oh my zsh
> [!NOTE]
> Use the following command to install powerlevel10k. This will add a new theme to your terminal. There are a lot of themes out there and I prefer this one.

`brew install powerlevel10k`

`echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc`

> [!TIP]
> Type `p10k configure` to access the built-in configuration wizard right from your terminal.


### Install Bat (Alternate to cat command)
> [!NOTE]
> Use the following command to install bat. This is an alternative to the cat command which is used to show the content of a file in the terminal. Bat adds more features like syntax highlighting.

`brew install bat`

### Install exa (Alternate to ls command)
> [!NOTE]
> Use the following command to install exa. This is an alternative to the ls command which is used to show the content of a folder in the terminal. exa adds more features like highlighting different texts.

`brew install exa`
