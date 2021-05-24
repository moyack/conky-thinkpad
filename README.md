# conky-thinkpad
Hi. This is a modification of a conky script developed by Ngọc Lương where the Thinkpad concept is the main character.
In order to run this script, you must have [Conky](https://github.com/brndnmtthws/conky) installed in your system.

Total credits to [Ngoc](https://github.com/lbngoc/conkyrc).

# Install
1. Download this code with this script: 
```shell
$ mkdir -p ~/.conky/Thinkpad && git clone https://github.com/lbngoc/conkyrc.git ~/.conky/Thinkpad
$ sed -i -e "s/ngoclb/$(whoami)/g" ~/.conky/Thinkpad/thinkpad-t440.conkyrc
```


Setup `thinkpad-wallpaper.png` as your desktop wallpaper.

# Usage

```
$ conky -q -c ~/.conky/Thinkpad/thinkpad-t440.conkyrc &> /dev/null
```

# Screenshot

- Thinkpad

![](thinkpad-screenshot.gif)

- Manjaro Tree

![](manjaro-tree-screenshot.png)
