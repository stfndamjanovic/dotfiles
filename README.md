# Dotfiles for macOS

This is my personal dotfiles. It's forked from [Dries Vints](https://github.com/driesvints/dotfiles) dotfiles, just changed enough to fit my personal preferences. If you want to know more about it, you can read the great [blog post](https://driesvints.com/blog/getting-started-with-dotfiles) that he wrote.

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

Restart computer to apply all changes and that's it. Your development env is ready.
