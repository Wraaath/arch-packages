# Arch Essentials
A collection of my essential packages on Arch Linux.

## Generating a package-list
Simple as <br />
`sudo pacman -Qqet > packages.txt` <br />
See also: https://wiki.archlinux.org/title/Pacman/Tips_and_tricks#List_of_installed_packages

## Installing from package-list
Just do a <br />
`yay -S packages.txt`
