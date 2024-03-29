# Configs & Scripts
A repository containing bash scripts and configuration files to get quickly up and running when switching to a new machine.


## Scripts

### linux_setup.sh

Automates the installation of the following programs on a new linux machine.

- neofetch
- htop
- git
- vim
- [mamba](https://github.com/conda-forge/miniforge)
- [vscode](https://code.visualstudio.com/docs/setup/linux)

**WARNING:** Compatible only with Debian-based distros using apt package manager (only tested on Ubuntu and Mint for now).


## Configs

### Visual Studio Code

`configs/Code/User/settings.json` contains user settings for vscode.
To apply those settings: paste its content in `~/.config/Code/User/settings.json`.
