- brew
  ```
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
- iterm2
- ```
  brew install iterm2
  ```
- zsh
  ```
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  ```
- auto suggestion

```
   git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
   nano ~/.zshrc
   plugins=(git zsh-autosuggestions)
   git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
   nano ~/.zshrc
   plugins=(git zsh-autosuggestions zsh-syntax-highlighting)

```

- nvm node
  ```
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
  ```
- python
- vscode
  - extensions
- gcc compiler
  ```
  brew search gcc
  brew install gcc
  ```
