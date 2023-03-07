# Dotfiles for macOS

This is my personal dotfiles. It's sort of combination
of different dotfiles from other devs, just changed enough to fit my personal
preferences.

## Installation

1. Generate a public and private SSH key
```
curl https://raw.githubusercontent.com/stfndamjanovic/dotfiles/HEAD/git/ssh.sh | sh -s "<your-email-address>"
```

2. Clone repository to dotfiles and run installation
```
git clone git@github.com:stfndamjanovic/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
./bootstrap.sh
```

Restart computer to apply all changes and that's it.