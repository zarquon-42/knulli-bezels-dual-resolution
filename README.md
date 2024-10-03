# knulli-bezels-dual-resolution

This repository contains bezel packs for Knulli utilizing functionality that allows for different bezels depending on the resolution.

These bezels have been taken from various sources and all credit should go to the
original creators.  If I missed credit please let me know.

For the system bezels I borrowed from [nvitaterna](https://github.com/nvitaterna/batocera_4_3_handheld_bezels)
(which in turn got them from [drkhrse](https://github.com/drkhrse/drkhrse_miyoo_bezels) and
[antiKk](https://github.com/antiKk/muOS-Overlays)) This includes the necessary `.info` files to
make them compatible with Batocera/Knulli. I have swapped some out with the bezels from
stock and adjusted some of the `.info` files.

For the game bezels, I used bezels from [Phanturian](https://www.reddit.com/user/Phanturian/)
as well as [The Bezel Project](https://github.com/thebezelproject) and created the
necessary `.info` files.

## Installation

Copy the desired bezel pack folder to the `/userdata/decorations` folder. Then, go
to "Game Settings" and set the decoration set to "dual_resolution" or "dual_resolution_with_arcade".

You may unset any integer scaling options you may have set for these consoles as the .info
files will set the integer scaling for you (for the systems with int scaling bezels).

## Acknowledgements

Big thanks to [drkhrse](https://github.com/drkhrse), [antiKk](https://github.com/antiKk)
and [Phanturian](https://www.reddit.com/user/Phanturian/) for creating the original bezels
and also thanks to [nvitaterna](https://github.com/nvitaterna) for many of the `.info` files.
