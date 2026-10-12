# t0rbem client

A client-side utility mod for Minecraft **1.21.11** (Fabric) with a ClickGUI, a movable HUD, per-module settings and a saved config.

## Features

**HUD** (all movable in the HUD editor): Watermark, FPS, Ping, CPS, Speed, Coords, Biome, Clock, Memory, Chunk Map, Keystrokes, Armor, Potion effects.

**Utility:** Flight, NoFall, AutoSprint.

**Render:** ESP, Storage ESP, Hole ESP, Sus Chunk, Fullbright, Zoom.

## Default keybinds

| Key | Action |
| --- | --- |
| Right Shift | Open ClickGUI |
| H | Toggle HUD |
| C (hold) | Zoom |
| G | Toggle Flight |

All keybinds can be changed in Minecraft's controls menu.

## Requirements

- Minecraft 1.21.11
- Fabric Loader 0.16.0 or newer
- Fabric API
- Java 21

## Install

1. Install Fabric Loader for Minecraft 1.21.11.
2. Put Fabric API and `t0rbem-client-<version>.jar` in your `mods` folder.
3. Start the game and press Right Shift.

## Config

Settings are saved in `config/t0rbem-client.json`, and chunk activity data in `config/t0rbem-chunks.json`.

## Building

```
./gradlew build
```

The jar ends up in `build/libs/`.

## Disclaimer

Some modules (Flight, NoFall, Speed, ESP, Sus Chunk) can give an advantage in multiplayer. Many servers forbid this and may ban you. Only use them where it is allowed, such as singleplayer or servers that permit it. You use this mod at your own risk.

## License

MIT.
