---
title: "Installing Mods"
linkTitle: "Installing Mods"
weight: 20
description: >
  How to install, view and manage your mods in Vortex.
---

{{% pageinfo %}}
At this time, using BeatVortex means you'll need to manually run `./IPA.exe -n` from your install directory to enable BSIPA after installing it.

This should be fixed in an upcoming version, once some Vortex quirks have been nailed down. If you've installed BSIPA with Mod Assistant, this is not needed.
{{% /pageinfo %}}

At it's core, installing mods is roughly the same as any Vortex-enabled game, just without the convenience of installing from Nexus Mods. Make sure you've added Beat Saber as a managed game in Vortex.

> If you haven't already, open the Games screen and click the **Manage** button on the Beat Saber icon under *Unmanaged*

There's three main ways to install mods:

- OneClick installs<sup>*preview*</sup> 
- Download in Vortex
- Install from archives

## OneClick Installation<sup>*preview*</sup>

One-click installation of custom songs from BeastSaber, BeatSaver or ModelSaber requires first enabling it in your Vortex profile settings.

> Enabling one-click installs in Vortex will most likely prevent Mod Assistant from handling one-click installs!

From the Profiles menu on the left, click the *Edit* button on your current profile (generally called **Beat Saber - Default**), and check the box to "Enable Vortex to handle Mod Assistant One-Click links".

You then need to restart Vortex (sorry!) and you're good to go. Open up BeatSaver/BeastSaber/ModelSaber and click any of the OneClick install links: Vortex should pick up the link in the background, fetch the song details and download the map (or mod) directly into your mod list. Install and Enable as per usual to deploy into your game.

#### A note on ModelSaber installs

Since ModelSaber models are not distributed as archives but just raw files, Vortex will warn you and will create a mod archive with just that one file. All of Vortex's install and deployments logic really works best with archives.

## Download in Vortex

Once you've added Beat Saber, you can jump over to the usual Mods screen using the menu on the left. You won't have any mods here, but if you click on the *But don't worry, I know a place...* dropdown, you'll get the choice of installing from BeatMods, BeatSaver or BeastSaber.

> This option will move to the *Get more mods* drop-down after you have installed your first mod.

You can browse mods using the built-in browser that appears and if you download the ZIP archive of any song (from BeastSaber) or mod (from BeatMods), Vortex will attempt to install it in the background for you. Close the browser to go back to your mod list then Install and Enable your mods as usual to use them in-game.

## Install from archives

You can also download mod/map archives directly from BeastSaber, BeatSaver, BeatMods or anywhere else you like and install them with Vortex. Simply use the *Install From File* button in the toolbar or drop them onto the drop zone at the bottom of the Vortex window.

> Be aware that installing from archives will often not include the full metadata so mods may be confusingly named. Double-click the mod in the mod list to change its name.

Please note that "raw" mods that aren't packaged in an archive (for example, the dll files provided by TrickSaber) will not work properly. Only archives are supported at this time.