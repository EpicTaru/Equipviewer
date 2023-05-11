# DEPRECIATED

## EquipViewer

Overlays your currently equipped items onto the screen anywhere. Basically just shows your equipment screen, but smaller, anywhere you want, and you can make it translucent. 

I am not the creator of this addon.  This repo is simply a Ashita packaged version of `EquipViewer` reverted to the version necessary for use on servers version locked PRIOR to the beginning of 2020.

There is a newer Ashita plugin version of `Equipviewer` available that should be used for servers that are on a version newer than the end of 2019. The newer version (and to submit issues with the current version of this addon) can be obtained at:

https://github.com/ProjectTako/ffxi-addons/tree/master/equipviewer


## Setup Instructions

1. Download the latest release from the "Releases tab."

2. Unzip the release package.

3. In the extracted folder, copy the unzipped directory `equipviewer-<version>` subdirectory to the Ashita addon directory.

4. Rename the `equipviewer-<version>` directory to `equipviewer`.

5. Load the addon via the `default.txt` script or Ashita `/addon load equipviewer` command.


## Commands

`/equipviewer pos[ition] x-value y-value` - Moves the equipment overlay to the desired location.

`/equipviewer size ##` - Changes the size of the overlay, valid choices for `##` are: `16`, `32`, `48`, `64`.
