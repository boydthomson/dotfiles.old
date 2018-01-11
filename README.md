Goal is to create a user experience with i3-gaps which is simple and clean, contemporary, and dark.

![alt text](https://i.imgur.com/IXwWCuu.jpg)
Wallpapers based on space themes.

* Screen locked based on timeout and lid close
* polybar with workspace icons
* colour scheme based on wallpaper
* transparent bar and unfocused windows

dependancies:
*  pip3 install pywal
*  polybar
*  slock
*  compton


# dotfiles
config files for my rice-in-progress
setup using instructions from https://developer.atlassian.com/blog/2016/02/best-way-to-store-dotfiles-git-bare-repo/

sample of adding a new file:  
config status  
config add .vimrc  
config commit -m "Add vimrc"  
config add .bashrc  
config commit -m "Add bashrc"  
config push  
