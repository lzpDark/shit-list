#### Problem

I can't use Ctrl+Alt+Left/Right to move backward/forward in idea ubuntu.



#### Fix

run this in terminal, after that key works:

```shell
gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-left "[]"
gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-right "[]"
```

see: https://stackoverflow.com/questions/47808160/intellij-idea-ctrlaltleft-shortcut-doesnt-work-in-ubuntu



#### Read

I don't know why, some other docs may help or not: (don't just want to read it)

https://wiki.ubuntu.com/Keybindings

 