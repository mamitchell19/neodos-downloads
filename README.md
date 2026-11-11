# NeoDOS downloads

NeoDOS is a modern, DOS-style operating system that starts from a USB stick - nothing is installed on the PC.

**Get it from [Releases](https://github.com/mamitchell19/neodos-downloads/releases/latest):**

| File | What it is |
|---|---|
| `NeoDOS-x.y-Live-USB.zip` | NeoDOS for a USB stick (works on PCs with BIOS or UEFI) |
| `NeoDOS-USB-Creator.zip` | A small Windows program that puts NeoDOS onto a USB stick |

## The easy way (Windows)

1. Download **NeoDOS-USB-Creator.zip**, open it and run **NeoDOS-USB-Creator.exe**.
   Windows may say "Windows protected your PC" because the program is new: click *More info*, then *Run anyway*.
2. Click **Download** - it fetches the newest NeoDOS by itself and checks it is undamaged.
   (Or choose a NeoDOS-x.y-Live-USB.zip you already downloaded - no need to unzip it.)
3. Plug in a USB stick (at least 1 GB; everything on it is erased), choose it and click **Write**.
   The stick is read back afterwards to make sure everything arrived.

Only USB drives are offered, so your computer's own disks cannot be erased by mistake.

## Starting a PC from the stick

Plug the stick in, switch the PC on and press its boot-menu key straight away (F12 on ThinkPads and Dell;
Esc, F8, F9 or F11 on others), then pick the USB stick. Secure Boot must be switched off in the PC's setup.

The stick can also be written with Rufus or balenaEtcher (unzip first and choose `neodos-live.img`),
or on Linux/macOS with `dd`.

NeoDOS is made by Michael Mitchell. This repository holds only the ready-to-use downloads.
