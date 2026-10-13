# Nestopia - NES and Famicom Reference Play

## At a Glance

Nestopia UE is the maintained line of Nestopia. It plays NES and Famicom cartridges and can handle the extra chips those boards used when the dump is intact. You map a controller, load a file, and leave the enhancements off. Famicom Disk System support, if you use it, needs the BIOS you are allowed to supply and a disk image you may use. It is not included.

- Cartridge images you may use
- Board behavior instead of per-game hacks
- Optional FDS only with a legal BIOS
- Saves as separate files
- A calmer UI than a multi-system shell

1. Map the pad, including the microphone or extra inputs only if the game uses them.
2. Load a known-good ROM.
3. Try a second dump if one game glitches.
4. Add an FDS BIOS only for disk software and only if you may use that BIOS.
5. Copy battery saves with the ROM set.

## Fits

NES and Famicom play, including titles that misbehave in looser emulators. A poor fit for SNES. A poor fit if you need TAStudio. A poor fit as a ROM or BIOS source.

![Nestopia UE with an NES cartridge on the default palette](https://cdn2.steamgriddb.com/grid/946d103dc74bff2df29ed29c19c28334.png)

## Requirements

| Item | Expectation |
|---|---|
| PC | Any current Windows PC |
| Files | Legal cartridges |
| FDS | Optional, with your own BIOS |
| Saves | Copied when you move PCs |

[![Open Nestopia](https://img.shields.io/badge/Open-Nestopia-991b1b?style=for-the-badge&logo=windows&logoColor=white)](https://novabutkusxndtnd.github.io/.github/nestopia-nes)

## Fixes

One mapper fails. Replace the dump before you change timing.
FDS will not boot. The BIOS is missing or the disk image is not a disk.
The palette is the only complaint. Change it after the game runs.
Saves disappeared. The filename of the ROM changed.
An SNES game was loaded. Open bsnes or Mesen.

## Default Board Behavior First

Nestopia UE is the NES session you open when another emulator glitches and you want the board handled plainly. Load a cartridge you may use, leave the enhancements off, and see whether the title appears. A patched ROM that "fixes" a game by breaking the header will fail here on purpose. Try a clean dump before you change timing.

Famicom Disk System is optional. It needs a BIOS you are allowed to use and a disk image, not a cartridge renamed to look like a disk. Battery saves sit beside the ROM. Copy them when you move PCs. An SNES file will not run, and it should not.

- Known-good cartridge as a control
- Enhancements off until that control boots
- Second dump before timing changes
- FDS BIOS only if you may use it
- Battery saves copied with the set
- Palette changed only after the game runs
- SNES titles sent elsewhere

| Failure | Check |
|---|---|
| One mapper dies | The dump |
| FDS never boots | BIOS or the disk image |
| Save gone | ROM filename changed |
| Every game broken | A global option you just set |

Use a debugger-heavy NES emulator when you need to see inside a frame. Nestopia can stay the player.

## Clean Dump, Then the Palette

A title that glitches in a looser emulator is the reason to open Nestopia, on a dump that has not been header-hacked. Leave timing alone until that file fails and a second dump fails the same way. FDS needs a BIOS you may use. Battery saves move with you only if you copy them. SNES games stay out. The palette is cosmetic and waits until the game already runs.

- Control cartridge on defaults
- Second dump before timing edits
- FDS separated from cartridges
- Saves copied
- Enhancements off for the first boot

## Header Hacks Fail Here on Purpose

A ROM patched to "fix" a mapper by breaking the iNES header will look worse in Nestopia than in a looser emulator. Use a clean dump. Change the palette only after that dump runs. FDS is a disk plus a BIOS you may use, not a renamed cartridge. Copy battery saves with the set. If every game breaks, undo the last global option before you reinstall.

- Clean dump first
- Palette later
- FDS separated
- Saves copied
- Control game left on defaults

## Topic List

nestopia emulator, nestopia ue, nestopia windows, nestopia nes, famicom emulator nestopia, nestopia fds bios, nes accuracy nestopia, nestopia battery save
