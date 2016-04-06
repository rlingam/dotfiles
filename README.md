![Screenshot of my desktop] (http://i.imgur.com/8wZ8IDL.png?1)
![Screenshot of my terminal] (http://i.imgur.com/vtXUPlM.png?1)

## dotfiles
dotfiles are how you personalize your system. These are mine

If you want to give these dotfiles a try make sure you read the code
over, things will go much smoothly that way, and even modify if you 
need to.

## Installation

### Method 1 (preferred)
You can now use the install script(untested but should work) located in ~/scripts/
you will have gitclone the directory somewewhere other than ~/ and extract the script and run it from there.

You can clone the repository wherever you want, but to install, add 
the files to your ~/ (/home/$USER/). 

for a cleaner solution (but more work) see Method 2

### Method 2
Install stow accordingly on your distro and simply
navigate to your home directory

` cd ~/`

make the dotfiles directory:

`mkdir Dotfiles`

change into the Dotfiles directory:

`cd Dotfiles`

clone the repo:

`git clone https://github.com/rlingam/dotfiles.git`

install the dotfiles onto your home directory:

`sudo stow -v -t ~/ dotfiles`

for dependencies, comment out the install portion (see install script) of install script then

`cd dotfiles/scripts/`

`./install`



## Whats Included
A lot of stuff,seriously, alot of stuff. Check out everything with a 
file browser and see what kind of stuff is there. Change what you 
want, remove what you don't need, and build on what you do use.

## Things you should know
The tiling folder has scripts which requires dependencies including 
slop or xrectsel, urxvt, wmctrl, xdotool, xwininfo. The tiling folder
is to be used with openbox.

the script folder may have dependencies too, make sure you check 
if it doesn't seem to work.

make sure you change the path files in your programs and especially
zsh/zshrc since file path will be different on your machine.

If fonts dont work properly make sure you have the right font
installed then refresh, if it still doesn't work make sure
you have the right font configured on the corresponding
config file.

## Thanks
Thanks for taking the time to view and hopefully download
my dotfiles. Special thanks to a fellow named twily whom
i originally forked my dotfiles off of.








