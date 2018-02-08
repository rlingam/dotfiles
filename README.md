<!--![Screenshot of my desktop](http://i.imgur.com/8wZ8IDL.png?1)-->
<!--![Screenshot of my terminal](http://i.imgur.com/vtXUPlM.png?1)-->
![screenshot of my desktop](https://i.imgur.com/axh346e.png)
## Setup
See the terminal pic above for some related information.

* Distro: `arch linux`
* Window Manager: `dwm`
* bar: `slstatus`
* Application Launcher: `dmenu`
* Login/Display Manager: `None`
* Compositor: `none`
* Terminal Emulator: `st`
* Shell: `zsh + oh-my-zsh`
* Font: `terminus`
* Notification Daemon: `none`
* Music Player: `cmus`
* Video Player: `mpv`
* Image Viewer/Desktop Wallpaper Display: `feh`
* IRC Client: `irssi`
* Text Editor: `vim`
* Browser: `qutebrowser`


## Dotfiles
dotfiles are how you personalize your system. These are mine

If you want to give these dotfiles a try make sure you read the code
over, things will go much smoothly that way, and even modify if you
need to.

## Whats Included
Although I try to keep everything as minimal as possible. Make sure 
you check out everything with a web browser and see what kind of 
stuff is there. Change what you want, remove what you don't need, 
and build on what you do use.

## Things you should know
The scripts in the scripts folder may have dependencies too, make sure you check the relative script for
its dependecies if something doesn't seem to work.

make sure you change the path files in your programs and especially
zsh/zshrc since file path will be different on your machine.

If fonts dont work properly make sure you have the right font
installed then refresh, if it still doesn't work make sure
you have the right font configured on the corresponding
config file.

## Installation
### Method 1

You can now use the install script to install these dotfiles.

Change to Download directory:

`cd ~/Downloads`

Clone the repo:

`git clone https://github.com/rlingam/dotfiles.git`

Change directory to install script:

`cd dotfiles/scripts/`

Run script:

`./install`

After the installation is succesfully finished, delete redundant dotfiles

`rm -rf ~/Downloads/dotfiles`

Beware however the script may not work properly as its not thoroughly tested.

Method two might be better if you want to manully install dependencies or fine tune the install to your liking.

### Method 2 
Make sure `ln` is installed on your distro and simply
navigate to your home directory

` cd ~/`

make the dotfiles directory:

`mkdir Dotfiles`

change into the Dotfiles directory:

`cd Dotfiles`

clone the repo:

`git clone https://github.com/rlingam/dotfiles.git`

install what you need or want onto your home directory:

`ln -s [where you want it installed] [what you want installed]`

for example

`ln -s /home/USER/suckless/dwm/config.h  /home/USER/Dotfiles/dotfiles/suckless/dwm/config.h`



for dependencies, you can install the dependencies manually by looking at the install script for the dependencies and installing them manually via package manager.


## Thanks
Thanks for taking the time to view and hopefully download
my dotfiles. Special thanks to everyone whose work i might've used to create these dotfiles.

