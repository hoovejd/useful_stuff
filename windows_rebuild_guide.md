# Introduction
These are the steps that I take when I reformat/rebuild my Windows desktop computer

## Backup
- backup any important files
- backup .ssh keys directory
- backup Putty session, see https://stackoverflow.com/questions/13023920/how-to-export-import-putty-sessions-list

## Create Windows Install Media
- create bootable thumb drive with latest version of Windows 10

## Create GParted Media
- create bootable thumb drive with latest GParted image

## Wipe Drives
- boot into GParted and wipe drive data

## Install Fresh Windows
- boot Windows Media thumb drive

## Re-Install Software
- Chrome
- VS Code
- Notepad++
- Google Messages
- FB Messenger
- Slack
- Zoom
- One Drive
- Nord VPN
- Steam
- Epic
- Origin
- Shotcut
- Inkspace
- VCarve
- Adobe Reader
- 7zip
- Putty

## Enable WSL

## Configure Git
- within the Ubuntu WSL, configure git:
```bash
git config --global user.name "Jarrod Hoover"
git config --global user.email hoov85@gmail.com
git config --global init.defaultBranch main
git config --global fetch.prune true
git config --global credential.helper cache
```

## Setup SSH Keys
📔 *Note: if using a private repo, you must have a password on your SSH key*

- create a new SSH key: ```ssh-keygen -t ed25519 -C "hoov85@gmail.com"```
- add it to GitHub

## Setup VS Code

## Setup Putty

