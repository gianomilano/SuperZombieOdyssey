# Super Zombie Odyssey Online

A zombie survival mod for **Super Mario Odyssey 1.0.0**: waves of zombies, rounds, perks, the Ray Gun, boss rounds, online co-op, and a hidden secret in the kingdoms.

Runs on emulators (e.g. Ryujinx) and on a Switch with Atmosphère.

## Download

Get the newest **`Super Zombie Odyssey Online <version>.zip`** under [Releases](../../releases/latest).

## Requirements

- Super Mario Odyssey **version 1.0.0** (no game update installed). Other versions are not supported.
- An emulator with mod support (e.g. Ryujinx) **or** a Switch with Atmosphère.

## Install – Emulator (PC)

1. Close the emulator.
2. Open the emulator's data folder (Ryujinx: `%APPDATA%\Ryujinx`, or the `portable` folder next to `Ryujinx.exe`).
3. Copy the folder `Emulator-MoonForge\mods` from the ZIP into that data folder, so that
   `mods\contents\0100000000010000\ZombieMode` and `mods\exefs_patches\ZombieMode` exist.
4. Copy the folder `romfs` from the ZIP into `mods\contents\0100000000010000\ZombieMode\romfs`.
5. Start Super Mario Odyssey 1.0.0.

## Install – Switch (Atmosphère)

1. Copy the contents of the ZIP's `Switch` folder to the root of the SD card.
2. Copy the folder `romfs` to `SD:\atmosphere\contents\0100000000010000\romfs`.
3. Remove old zombie files first if an older version was installed.

## Playing online

- The **host** starts `Zombie Server\ZombieServer.exe` and shares the join code.
- The other players jump into the **Online painting** in the start room and type the join code (e.g. `K7QM-2XPA`).
- Everyone needs the same version.
- The join code contains the host's IP address – only share it with people you play with.

## Updates

Run `Zombie Server\ZombieUpdater.exe`. It downloads only what changed and installs it for the emulator and/or the Switch SD card.

---

## Deutsch (kurz)

Zombie-Survival-Mod für **Super Mario Odyssey 1.0.0** (Emulator oder Switch mit Atmosphère).
Download unter [Releases](../../releases/latest) – die Installation steht auch als `README.txt` im ZIP.
Online: Der Host startet `ZombieServer.exe` und gibt den Join-Code nur an Mitspieler weiter; die Mitspieler springen im Startraum ins Online-Bild und geben den Code ein.

---

*This is a fan-made mod. Super Mario Odyssey is © Nintendo. You need your own legally obtained copy of the game.*
