## EquipViewer

Overlays your currently equipped items onto the screen anywhere. Basically just shows your equipment screen, but smaller, anywhere you want, and you can make it translucent. 

I am not the creator of this addon.  This repo is simply a Ashita packaged version of a depreciated version of `EquipViewer` that is reverted to the version necessary for use on servers version-locked <strong>PRIOR</strong> to the beginning of 2020. 

As I do not own this addon, I cannot assist with issues regarding it.  I am able, though, to assist with issues related to the icon images used by this addon, as well as the addition of icon images for this addon if they are found to be missing (missing icon images display as a `white box` in the addon overlay). Please submit issue tickets for either of these issue types at: https://github.com/EpicTaru/Equipviewer/issues

There is a newer/current Ashita plugin version of `Equipviewer` available that <ins>should</ins> be used for servers that are on a version <strong>NEWER</strong> than the end of 2019. The newer/current version, as well as to submit issues with the newer/current version, is located at:

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
