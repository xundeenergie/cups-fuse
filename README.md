# fuse-cups
Mount all system-printers in $HOME/Printers

## Activation via systemd --user
to activate the fuse-filesystem run
```
	systemctl --user enable --now cups-fuse.path
```

create a directory with

```
	mkdir ~/Printers
```

browse your printers

```
	ls ~/Printers
```


