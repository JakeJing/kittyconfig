# kittyconfig
configuration file for my kitty on mac

1. install kitty on mac
> curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin

2. set the kitty as the default terminal

system preference - default Apps - click the "default Apps" - URLS - x-man-page - set iTerm as the default application

3. set shortcut to initialize the terminal

System Preferences -> Keyboard -> Shortcuts -> Services -> New iTerm2 window here

I set the shortcut as: (shift+command+1)

4. put the kitty.conf inside the folder of ~/.config/kitty/

wget https://raw.githubusercontent.com/JakeJing/kittyconfig/master/kitty.conf -P ~/.config/kitty/

