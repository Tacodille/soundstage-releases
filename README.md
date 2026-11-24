# Soundstage releases

Builds of [Soundstage](https://github.com/Tacodille/soundstage), a GPose studio plugin for FFXIV: pick a Scene and it
sets the lights, backdrop, props, camera, ReShade look and pose in one click. Source and full docs are in that repo.

## Install

1. In game, `/xlsettings` > Experimental > Custom Plugin Repositories. Add both of these, tick them, save:
   - `https://raw.githubusercontent.com/Tacodille/soundstage-releases/main/repo.json` (Soundstage)
   - `https://github.com/universalconquistador/Stagehand/releases/latest/download/repo.json` (Stagehand, which does the lights and props)
2. `/xlplugins`: install Soundstage, Stagehand and Brio. Switch IPC on in Brio's settings.
3. Go into GPose and type `/soundstage`. The Status tab says what's working and what isn't.

`plugins/Soundstage/soundstage.addon64` is the optional ReShade add-on. Close the game, copy it into the folder with
`dxgi.dll`, start the game again. Skip it if you don't use ReShade.

Version 0.1 is a test build, so expect rough edges. `/soundstage test` walks through a checklist.
