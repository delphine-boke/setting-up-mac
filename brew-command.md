should you encounter

``zsh: brew: command not found``

while trying to see which version of brew is installed. do this:

``/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"``

which installs brew.  you may hit enter/return to continue with the installation as usual.

if the issue of brew persists, it means brew is not added to path. so:

``echo "export PATH=/opt/homebrew/bin:$PATH" >> ~/.zshrc``

lastly, for good measure, you may run:

``brew doctor``

to fix any issues pertaining brew.

make sure you know your version of brew by ``brew --version`` and use the latest version by ``brew update`` if need be.

