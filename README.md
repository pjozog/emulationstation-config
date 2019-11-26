# Instructions

Before doing anything, have `~/.emulationstation` point to the
`emulationstation/` directory in this repo.

Download `retroarch` using snap:
```
$ sudo snap install retroarch
```

To set up a new console:

1. Start `retroarch`.

1. Download the core you want.

1. Load a game using said core.

1. While playing press `F1`. Under `Shaders`, select the shader options you want
   (I'd suggest `crt/crt-easymode` for consoles with 16-bit processors or
   less). Under `Shaders -> Save`, save the current options to be core-specific.

1. Set the `input_player1_*` entries in a config file specific to the console.

1. Update `emulationstation/es_systems.cfg` to use this new console (use the
   `--appendconfig` option for the new config file.
