# bspwm-dotfiles
### Additional Dependencies
* sxhkd
* compton/picom
* nitrogen
* polybar
* rofi
* xbacklight
* mpd
* xkeyboard
* i3lock

### Instructions on Solus
```
sudo eopkg install bspwm picom nitrogen polybar xbacklight mpd xkeyboard-config
```

Edit `/etc/X11/xorg.conf.d/70-touchpad-settings.conf` to get tapping and natural scrolling:
```
Section "InputClass"
	Identifier			"Touchpads"
	MatchIsTouchpad			"on"
	Option	"Tapping"		"on"
	Option	"NaturalScrolling"	"true"
EndSection
```

