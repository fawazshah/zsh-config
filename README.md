# My .zshrc config file

This is made to work with my fork of robbyrussell's [oh-my-zsh](https://github.com/fawazshah/oh-my-zsh).

## Changes from the original

* Uses the powerlevel9k theme
* Includes `context`, `dir` and `vcs` on the left hand side of the command prompt
* Includes `status`, `dir_writable`, `time`, `load`, `ram` and `disk_usage` on the right hand side of the command prompt
* Loads popular plugins such as `git`, `node` and `pip`
* Includes aliases for `vim` and `sudo vim`, my most commonly used commands

## Installation instructions

Run the following commands:

```
cd ~
git clone https://github.com/fawazshah/zsh-config
ln -s zsh-config/.zshrc .zshrc
source .zshrc
```
