#### The Hazardless Project

A full-game hazard-removal overhaul for Sonic 3 A.I.R. that strips out all spikes, badniks, missiles, and stage hazards across every main Zone (Angel Island through Doomsday Zone), removes unnecessary bumpers in the Glowing Spheres Bonus Stage, and replaces every pre-placed red sphere across all 16 Blue Sphere Special Stages with star bumpers.

#### Features

* Hazard-Free Main Game (AIZ – DDZ): 

  * Removes all badniks, spikes, missiles, flames, lasers, and stage hazards from Angel Island Zone all the way through Doomsday Zone.
* All 16 Special Stages Modified:

  * Covers both Sonic 3 (Stages 1–7 + Secret 8th Stage) and Sonic & Knuckles (Stages 1–7 + Secret 8th Stage).
  * Pre-Placed Red Spheres Removed: All existing red spheres on the map have been replaced with bounce bumpers, though blue spheres you collect will still turn into red spheres as usual.
* Cleaned-Up Pachinko Bonus Stage: 

  * Removes unnecessary bumpers from the Glowing Spheres (Pachinko) checkpoint bonus stage.
* Clean, Native Modding Architecture:

  * Uses leveldata.json for main-zone and bonus-stage object layouts alongside rominjections.json for Special Stage layouts—keeping everything lightweight with zero script conflicts. However, this mod makes the achievements "Electrofishing" and "Fluffy Fur Must Not Get Wet" impossible due to the lack of enemies and the layouts being changed. "Millionaire" will become harder, but the lack of enemies and tweaks to the layouts can give you a better Time and / or Ring Bonus. Compatible with mostly all platforms, such as Windows x64, Android, iOS, Linux, etc. MacOS is undetermined so far.
  * STRICTLY requires the Sonic 3 and Knuckles layouts. The Sonic 3 A.I.R. layouts will make Knuckles' spawn in AIZ1 broken and may break other things.

#### Installation

* PC (Windows / Linux / Steam Deck)

1. Download and extract the mod archive so that the folder containing mod.json is intact.
2. Move the extracted mod folder into your Sonic 3 A.I.R. mods directory: 
  * Windows: %AppData%\Sonic3AIR\mods\
  * Linux / Steam Deck: ~/.local/share/Sonic3AIR/mods/
3. Launch Sonic 3 A.I.R., open Mods, and enable "The Hazardless Project".

* Mobile (iOS / Android)

1. Download the mod .zip archive to your device.
2. Open Sonic 3 A.I.R. and use the built-in in-game mod/file manager (under Mods > Open Mods Folder / Install Mods) to import the .zip archive directly.
3. Enable "The Hazardless Project" in your active mods list.

(Recommended: Place this mod above any other level-layout mods so your custom stages take priority.)

#### Compatibility Notes

* Compatible:

  * Custom characters and Extra Slot character mods
  * Palette modifiers (for main zones and Special Stages)
  * .bmp texture/sprite replacements for level chunks, Special Stage spheres, rings, and bumpers
  * Music, sound, and HUD/UI mods
  * Useott's Unburnt AIZ2, 100% tested and compatible
* Incompatible:

  * Other mods that modify leveldata.json object layouts for main zones (AIZ–DDZ) or the Pachinko Bonus Stage, as well as mods that overwrite the main Sonic 3 / Sonic & Knuckles Special Stage layout ROM addresses.
* Blue Sphere Minigame: Only the main game Chaos Emerald and Super Emerald Special Stages are modified; standalone Blue Sphere mode stages remain untouched.

#### Credits & Tools Used

* Mod Creator: vFracture
* Tools: S3SSEdit at https://info.sonicretro.org/Sonic_3_Special_Stage_Editor, SonLVL, skdisasm at https://github.com/sonicretro/skdisasm, and Clownacy's Kosinski Compression Tools.

#### Changelog

* No changes yet!

#### v1.0.0-alpha1

* First release, most likely has some bugs.
* Removed all spikes, badniks, missiles, and hazards across all main zones (AIZ1–DDZ) via leveldata.json.
* Removed unnecessary bumpers from the Glowing Spheres (Pachinko) Bonus Stage.
* Replaced all pre-placed red spheres with bumpers across all 8 *Sonic 3* Special Stages and all 8 *Sonic & Knuckles* Special Stages via rominjections.json.