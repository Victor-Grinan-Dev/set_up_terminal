# set_up_terminal
commands to set the terminal
xcode-select --install
#from url: https://brew.sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew update
brew install bash

sudo nano /etc/shells
# inside editor add: 
/usr/local/bin/bash
chsh -s /usr/local/bin/bash

nano .bash_profile
#edit desired commands inside

#nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm


brew install fortune
brew install cowsay
brew install git
brew install vcprompt
brew install spectacle
brew install alfred

brew cask install firefox
brew install iterm2


