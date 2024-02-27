# git-pull-force

**NOTE!**

This is a destructive script. It will overwrite the local files with whatever is found on git origin.

## Usage

Overwrites local files with latest origin files

```
Usage: $0 [-y|--yes] [-h|--help] [branch-name]
  -y, --yes    Bypass confirmation prompt.
  -h, --help   Display this help message.

If no branch-name is provided, defaults to 'main'.
```

## Installation

Please remember that this is a random bash script on the internet. Make sure to check what you are actually adding to your computer.

1. `wget -q -O - https://raw.githubusercontent.com/jsuomi/git-pull-force/main/git-pull-force > git-pull-force`
2. `sudo mv git-pull-force /usr/local/bin/git-pull-force`
3. `sudo chmod +x /usr/local/bin/git-pull-force`
