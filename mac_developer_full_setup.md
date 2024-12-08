[Mac Developer Full Setup Youtube Video](https://www.youtube.com/watch?v=hBQamXaykww)

Install Oh my zsh: 

    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" 

Autosuggestions: 

    git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions 

Syntax highlighting: 

    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting 

Fast Syntax Highlighting: 

    git clone https://github.com/zdharma-continuum/fast-syntax-highlighting.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/fast-syntax-highlighting 

Autocomplete: 

    git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git $ZSH_CUSTOM/plugins/zsh-autocomplete 

Show hidden file: 

    defaults write com.apple.finder AppleShowAllFiles YES; killall Finder 

Find the line which says: plugins=(git) 
Replace with: plugins=(git zsh-autosuggestions zsh-syntax-highlighting fast-syntax-highlighting zsh-autocomplete) 

Xcode Command Line Tools: 

    xcode-select --install 

Home brew: 

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
