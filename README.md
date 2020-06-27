# dotfiles
Configuration.

### Requirements
- Clone this repository in your home directory
- Increase mouse speed - `defaults write -g com.apple.mouse.scaling  5.0`
- [Homebrew](https://brew.sh/)
- [Oh my zsh](https://ohmyz.sh/)
- Add golang path to `.zshrc`
```
export GOPATH=$HOME/Go
export GOROOT=/usr/local/opt/go/libexec
export PATH=$PATH:$GOPATH/bin
export PATH=$PATH:$GOROOT/bin
```

### Give permissions to shell scripts
`$ chmod +x ./install.sh && chmod +x ./brew.sh`

### Run
`$ ./install.sh [YOUR HOME PATH]`