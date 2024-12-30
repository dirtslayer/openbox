# Openbox configuration

place files in ~/.config/openbox
```
autostart
menu.xml
rc.xml
```

### launch openbox from desktop manager 

pick one of: ly,lightdm,gdm,sddm

```
  systemctl start ly
```

### launch openbox with startx

this will ignore .config/openbox/autostart

```
  startx /usr/bin/openbox
```

