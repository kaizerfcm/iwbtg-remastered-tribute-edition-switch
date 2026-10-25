## Nintendo Switch build

This repository hosts the **Nintendo Switch** homebrew release of I Wanna Be The Guy: Remastered Tribute Edition.

**Download:** [IWBTGR-TributeEdition-Switch.zip](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-switch/releases/download/v1.6.6.6/IWBTGR-TributeEdition-Switch.zip) and, for emulators or title installers,
[IWBTGR-TributeEdition-Switch-01005666A1B70000.nsp](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-switch/releases/download/v1.6.6.6/IWBTGR-TributeEdition-Switch-01005666A1B70000.nsp) ([latest release](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-switch/releases/latest))

**Install:** on a Switch running custom firmware, unzip and copy the `switch` folder to the root of the SD card
(you get `switch/iwbtgrt/iwbtgrt.nro`), then launch it from the Homebrew Menu. Title-override mode (hold R while starting
a game) is recommended so the game gets the full memory; applet mode (Album) also works.
Saves go to `sdmc:/switch/iwbtgrt/save`. The NSP (title ID `01005666A1B70000`) is for emulators or installing to NAND.

| Switch | Action |
| --- | --- |
| D-pad / left stick | Move |
| B | Jump |
| Y | Shoot |
| X | Restart |
| + | Pause |
| R | Skip |
| A | Back |

Controls can be remapped in *Options*. Joy-Con, Pro Controller and handheld mode work.

**Other platforms:** [PS5](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition) | [Windows](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-windows) | [Linux](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-linux) | [Android](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-android) | [itch.io](https://shmshp.itch.io/iwbtgrt)

---

# I Wanna Be The Guy: Remastered Tribute Edition

<img src="sce_sys/icon0.png" width="128" align="right">

Native PS5 homebrew port of *I Wanna Be The Guy: Remastered*, version 1.6.6.6. This repository hosts the PS5 release;
each other platform has its own release repository.

## Platforms
| Platform | Repository |
| --- | --- |
| PS5 (title ID PPSA99616) | this repository, [kaizerfcm/iwbtg-remastered-tribute-edition](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition) |
| Windows x64 | [kaizerfcm/iwbtg-remastered-tribute-edition-windows](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-windows) |
| Linux x64 | [kaizerfcm/iwbtg-remastered-tribute-edition-linux](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-linux) |
| Nintendo Switch (homebrew) | [kaizerfcm/iwbtg-remastered-tribute-edition-switch](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-switch) |
| Android | [kaizerfcm/iwbtg-remastered-tribute-edition-android](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-android) (no release yet) |

Also on itch.io: [shmshp.itch.io/iwbtgrt](https://shmshp.itch.io/iwbtgrt)

## Download (v1.6.6.6)
| Platform | File |
| --- | --- |
| PS5 (title ID PPSA99616) | [IWBTGR-TributeEdition-PS5-PPSA99616.zip](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition/releases/download/v1.6.6.6/IWBTGR-TributeEdition-PS5-PPSA99616.zip) |
| Windows x64 | [IWBTGR-TributeEdition-win64.zip](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-windows/releases/download/v1.6.6.6/IWBTGR-TributeEdition-win64.zip) |
| Linux x64 | [IWBTGR-TributeEdition-linux-x64.tar.gz](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-linux/releases/download/v1.6.6.6/IWBTGR-TributeEdition-linux-x64.tar.gz) |
| Nintendo Switch (homebrew) | [IWBTGR-TributeEdition-Switch.zip](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition-switch/releases/download/v1.6.6.6/IWBTGR-TributeEdition-Switch.zip) |

Checksums: [SHA256SUMS.txt](https://github.com/kaizerfcm/iwbtg-remastered-tribute-edition/releases/download/v1.6.6.6/SHA256SUMS.txt) for the PS5 release; each platform repository's release lists its own.

## Requirements
- **PS5:** a jailbroken console with a homebrew payload loader (for example etaHEN or elfldr), ShadowMountPlus
  (or another tool that registers apps from `/data/homebrew`), and FTP or a USB drive to copy the files.
- **Windows:** Windows 10/11 x64.
- **Linux:** x64 with glibc 2.38 or newer (Ubuntu 24.04, Fedora 39, Debian 13 or later). SDL2 is included.

## Install
**PS5**
1. Unzip `IWBTGR-TributeEdition-PS5-PPSA99616.zip`.
2. Copy the `PPSA99616` folder to `/data/homebrew/` on the console.
3. Let ShadowMountPlus scan (or reboot). The game appears on the home screen.

To update, copy the new folder over the old one. Saves are kept in `/data/iwbtgr/save`.
If you installed the `PPSA99099` folder earlier on 24 October 2026, copy `PPSA99616` and then delete
`/data/homebrew/PPSA99099`; your saves stay where they are.

**Windows:** unzip and run `IWBTGR.exe`. **Linux:** extract and run `./iwbtgr.sh`.

## Controls
| PS5 | PC (default) | Action |
| --- | --- | --- |
| D-pad / left stick | Arrows | Move |
| Cross | Shift | Jump |
| Square | Z | Shoot |
| Triangle | R | Restart |
| Options | P | Pause |
| R1 | S | Skip |
| Circle | Backspace | Back |

Controls can be remapped in *Options*. On PC, F11 toggles fullscreen. Controllers work on PC too.

## Credits
- Michael "Kayin" O'Reilly: *I Wanna Be The Guy*
- Cherry Treehouse: *I Wanna Be The Guy: Remastered* (Natsu & Renko, Floogle & renex, Midoru, Koala,
  Roaming97 and everyone in the game's credits)
- shaman: *I Wanna be the Tribute*
- shaman: the version 1.6.6.6 patch and extras (PS5 and PC editions)
- Emoji graphics: [Twemoji](https://github.com/jdecked/twemoji) by Twitter, Inc and other contributors,
  licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Built with the [PS5 payload SDK](https://github.com/ps5-payload-dev/sdk) and SDL2.

## Source
This repository only hosts the releases. The source code is kept in a private repository.
The runtime is GPL-3.0-or-later (`LICENSE`); the games' own content belongs to their authors.
