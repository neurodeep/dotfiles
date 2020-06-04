# dotfiles
Bash customizations and other dot files

Just copy everything into the Home folder.

Alternatively, you can hardlink everything to a custom folder to be able to pull changes (if any ;)).

```
ln dotfiles/.gitconfig .gitconfig
echo '#!/bin/bash' > ~/.bashrc
echo '. dotfiles/.bashrc' > > ~/.bashrc
