# Regolith OS setup

https://regolith-desktop.com/

This repository contains the folder: `~/.config/regolith3`

Most of the visual tweaking is done in the `Xresources` file. To apply the changes, run:

```
regolith-look refresh
```

Restart i3: `Win + Shift + R`


## Unity redraw-on-focus fix

Script auto-launched in `i3/config.d/50_unity`.

```bash
# install dependencies
pip3 install i3ipc pynput

# run the script
python3 ~/.config/regolith3/unity_fix.py
```
