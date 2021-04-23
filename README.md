# firefox-playerctl-notifier
The script to automatically send a notification when has some event occurs to firefox media player

![](https://i.imgur.com/OLSU3mJ.png) 
## Dependency
- ![playerctl](https://archlinux.org/packages/community/x86_64/playerctl/)
- ![libnotify](https://archlinux.org/packages/extra/x86_64/libnotify/)
- ![dunst](https://archlinux.org/packages/community/x86_64/dunst/)

## Install
- Symlink it to /usr/bin/
``` bash 
sudo ln -s firefox_playerctl_notifier /usr/bin/firefox_playerctl_notifier 
```
## Usage
``` bash 
firefox_playerctl_notifier <DELAY_IN_MS>
```
e.g.
``` bash 
firefox_playerctl_notifier 500 &
```
## Authors
* ENEmy ([@ENE_mee](https://twitter.com/ENE_mee))
