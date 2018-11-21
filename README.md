# Michael's GNU/Linux Dotfiles

I'd just like to interject for a moment. What you’re referring to as Linux, is in fact, GNU/Linux, or as I’ve recently taken to calling it, GNU plus Linux. Linux is not an operating system unto itself, but rather another free component of a fully functioning GNU system made useful by the GNU corelibs, shell utilities and vital system components comprising a full OS as defined by POSIX.
Many computer users run a modified version of the GNU system every day, without realizing it. Through a peculiar turn of events, the version of GNU which is widely used today is often called “Linux”, and many of its users are not aware that it is basically the GNU system, developed by the GNU Project. There really is a Linux, and these people are using it, but it is just a part of the system they use.
Linux is the kernel: the program in the system that allocates the machine’s resources to the other programs that you run. The kernel is an essential part of an operating system, but useless by itself; it can only function in the context of a complete operating system. Linux is normally used in combination with the GNU operating system: the whole system is basically GNU with Linux added, or GNU/Linux. All the so-called “Linux” distributions are really distributions of GNU/Linux.

## Packages

If you're using Fedora 29, these are all the main packages I install. On other distros you may already have these, or may need additional ones.

To install them automatically, use my installer here: [MOOBS](https://github.com/michaelauderer/MOOBS)

- i3-gaps (window manager)
- i3blocks (i3 status bar configuration)
- i3lock (lock screen for i3, requires password to get back in)
- rxvt-unicode (urxvt) (console)
- vim (cli text editor)
- bash (shell)
- ranger (cli file browser)
- w3m (preview images in ranger)
- google-chrome (access to our overlord's internet)
- calcurse (cli calendar/todo-list)
- compton (for window transparency and fixes screen tearing)
- pywal (generates color scheme based on wallpaper)
- feh (image viewer, used for wallpaper)
- arandr (UI for screen adjustment)
- scrot (takes quick screenshots)
- unar (extracts .rar archives)
- Hack Nerd Font (really nice font IMO)

## Distro

Fedora 29... but these configs, scripts, and programs should work on almost any distro. In theory.

## Installation

Running the following commands will clone this repo and pull my dotfiles into your home folder. This method may be destructive of your existing configs, so take caution.

```sh
cd ~
git init
git remote add origin https://github.com/michaelauderer/dotfiles
git fetch
git reset origin/master
git checkout -t origin/master
git checkout -- .
```


