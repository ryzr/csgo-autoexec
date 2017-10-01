# CS:GO Autoexec


## Installation

Download `_autoexec` folder and save it to your CS:GO config directory: `${INSTALL_DIR}/Counter-Strike Global Offensive/csgo/cfg`

Next update (or create) your autoexec.cfg in the config directory. Update or set the contents of the file to something like this:

```
clear

exec _autoexec/_main.cfg

host_writeconfig
```

## Configuration

**_main.cfg**

Base scaffolding. You can change your preferred colour and a few other misc settings here

**aliases.cfg**

Contains a bunch of help aliases to use for practice, gamemodes and hud shortcuts

**audio.cfg**

Basic sound settings

**crosshair.cfg**

Your default crosshair configuration. This is needed particularly if you use the `bigxhair` bind toggle

**hud.cfg**

HUD placement, colours, etc

**keybinds.cfg**

Set up keybinds, link with aliases that I've set up, etc

**mouse.cfg**

Mouse sensitivity settings

**optimizations.cfg**
You shouldn't need to touch this unless a particular setting is giving you troubles

## License

You're free to use, modify, redistribute, etc as you please. Attribution appreciated but not necessary.
