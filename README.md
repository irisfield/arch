## Liveiso
After booting into the liveiso, connect to the internet connection.

### Console Font
List the font options.
```sh
ls /usr/share/kbd/consolefonts/ | grep 'ter-[0-9]\+n'
```
Set the console font size from one of the options.
```sh
setfont ter-124n 
```
### Git
Clone this repo.
```sh
pacman -Sy git
git clone https://github.com/irisfield/arch.git
```
