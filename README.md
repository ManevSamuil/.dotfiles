# My Dotfile

## TODO:
- use stow (GNU Stow) to symlink my configs
- move my VSCODE HERE 

## Commands:

- dry run (simulation): stow -n -v -t ~/ --ignore=README.md %package_name%
    - example: stow -n -v -t ~/ --ignore=README.md vscode
- real: stow -v -t ~/ --ignore=README.md *
