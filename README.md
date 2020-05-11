This plugin is a fork of https://github.com/alexanderjeurissen/ranger_devicons 

# File icons for the Ranger file manager

This plugin introduces a new linemode that prefixes file names with a file icon

![image](https://github.com/glaulher/ranger_devicons/blob/master/screeshoot.png)

## Prerequisites
This plugin uses glyphs from a patched material icons. So in order for this plugin to work you need to
install a material icons.
https://github.com/google/material-design-icons/blob/master/iconfont/MaterialIcons-Regular.ttf

create folder:

mkdir ~/.fonts
cd ~/.fonts

download font:

wget https://github.com/google/material-design-icons/raw/master/iconfont/MaterialIcons-Regular.ttf

update cache

fc-cache -vf ~/.fonts/
 

To install, just clone the repo into the plugins folder:
```bash
git clone https://github.com/glaulher/ranger_devicons.git ~/.config/ranger/plugins/ranger_devicons
```
Then add `default_linemode devicons` to your `rc.conf`.
