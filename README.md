# base windows fonts

The entire collection of fonts that ship with Windows 10 by default, including a few extra specifically for Garry's Mod. Intended to be used for Garry's Mod running through Proton or any other program running through WINE, but will also work for any purpose on your system. 

This is because due to licencing concerns Garry's Mod and the Linux Project cannot include these fonts without facing steep licencing costs or legal repercussions. I've put these fonts here so that anyone running Linux doesn't have to go through the hell that I did of setting up a VM with a shared folder just to fetch a folder of fonts.

# Installation

- Install the source .zip or clone the repo to your machine using `git clone`.
- *[If you downloaded the ZIP]* Extract the zip's contents.

**For Garry's Mod:**
- Paste the contents of the folder to `/home/{USER}/.local/share/Steam/steamapps/compatdata/4000/pfx/drive_c/windows/Fonts/`.
- Restart Garry's Mod.

**For installation system-wide:**
- Paste the folder (or its contents) to `/usr/local/share/fonts/` or alternatively `/usr/share/fonts`.
- Run `fc-cache -fv` in bash.
