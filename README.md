# Cowfiles

Extra files for cowsay

## Installation

Assuming that cowsay is already installed...

```shell
git clone https://github.com/spenserblack/cowfiles.git $HOME/cowfiles
```

### Bash

```bash
# .bashrc
export COWPATH="/usr/share/cowsay/cows:$HOME/cowfiles"
```

### Fish

```fish
# config.fish
set -x COWPATH "/usr/share/cowsay/cows:$HOME/cowfiles"
```
