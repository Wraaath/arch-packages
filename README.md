# Arch Packages
A collection of packages that I use on Arch.

## Generating a package-list
Simple as <br />
`sudo pacman -Qqet > packages.txt` <br />
See also: https://wiki.archlinux.org/title/Pacman/Tips_and_tricks#List_of_installed_packages

## Install with yay on Arch based
Just do a <br />
`yay -S packages.txt`

## Install with apt on Debian based
Just do a <br />
`apt install packages.txt`
