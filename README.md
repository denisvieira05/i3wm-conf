# i3wm-conf
My i3wm personal configurations. 
To make it work, we need to install some tools.

## Init Configuration
Well, everything is setup inside the i3wm, so it's required.

```bash
    sudo apt-get install i3wm
```

## Bluetooth utils
`bluetooth-wizard`


## File Explorer
If you're not used with terminal to explore file, you can use **Thunar** to do so.
It's pretty similar to *gnome file version*.
```bash
    sudo apt-get install thunar
    sudo apt-get install gnome-icon-theme-full
```

## Better font rendering
```bash
    sudo add-apt-repository ppa:no1wantdthisname/ppa
    sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get install fontconfig-infinality
```

## Install Yosemite SanFrancisco Font
Look on the link on the end of this file to know how to use it, cuz it's a manual task.
```bash
    wget https://github.com/supermarin/YosemiteSanFranciscoFont/archive/master.zip
    unzip YosemiteSanFranciscoFont-master.zip
    mv YosemiteSanFranciscoFont-master/*.ttf ~/.fonts/
    rm -rd YosemiteSanFranciscoFont-master
```


## Custom Lockscreen
If you want to change the LockScreen look the links.
https://www.reddit.com/r/unixporn/comments/3358vu/i3lock_unixpornworthy_lock_screen
https://git.fleshless.org/misc/tree/i3lock-extra

## To take printscreen and pixelate it, needed to use custom lockscreen
```bash
    sudo apt-get install scrot imagemagick
```

## Tutorials
* [i3wm: Jump Start (1/3)](https://www.youtube.com/watch?v=j1I63wGcvU4)
* [i3wm: Configuration (2/3)](https://www.youtube.com/watch?v=8-S0cWnLBKg)
* [i3wm: How To "Rice" Your Desktop (3/3)](https://www.youtube.com/watch?v=ARKIwOlazKI)

## Credits

This wiki uses as a base in the awesome referencies
- [i3wm-conf](https://github.com/brunodles/i3wm-conf) by Bruno de Lima .
- [dotfiles](https://github.com/andersonfernandes/dotfiles) by Anderson Fernandes .
