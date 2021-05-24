# conky-thinkpad
Hi. This is a modification of a conky script developed by Ngọc Lương where the Thinkpad concept is the main character.
In order to run this script, you must have [Conky](https://github.com/brndnmtthws/conky) installed in your system.

This script was based on the work of [Ngọc](https://github.com/lbngoc/conkyrc). Total credits to him.

# Install
1. Download this code with this script: 
```shell
mkdir -p ~/.conky/Thinkpad && git clone https://github.com/moyack/conky-thinkpad.git ~/.conky/Thinkpad
```
2. Create an autostart script with your favorite text editor. This is one example for KDE:
```ini
[Desktop Entry]
Comment=
Exec=(killall conky; sleep 20s; conky -q -c ~/.conky/Thinkpad/thinkpad.conkyrc &> /dev/null) &
GenericName=
Icon=system-run
MimeType=
Name=Start conky-Thinkpad
Path=
StartupNotify=true
Terminal=false
TerminalOptions=
Type=Application
X-DBUS-ServiceName=
X-DBUS-StartupType=
X-KDE-SubstituteUID=false
X-KDE-Username=
```
And save it as `Init Conky.desktop`.
If you don't use KDE, you can find an equivalent way to do an autostart file, and just ensure to set the command suggested in the **Usage**.

3. Set `thinkpad-wallpaper.png` as your desktop wallpaper.

# Usage

```
conky -q -c ~/.conky/Thinkpad/thinkpad.conkyrc &> /dev/null
```
You will notice that the script will load the parts of the script in sequence. That's all!! enjoy it :D

# Screenshot

- Thinkpad

![](https://raw.githubusercontent.com/moyack/conky-thinkpad/main/Screenshot.png)
