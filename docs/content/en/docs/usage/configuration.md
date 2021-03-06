---
title: "Configuration"
linkTitle: "Configuration"
weight: 30
description: >
  How to configure and customise your mods
---

### Customising metadata

You can customise the basic metadata of any of your mods (name, author, notes etc) using Vortex's built-in sidebar. Just double-click on the name of any mod in your mod list and you'll get a small dialog where you can change the name and author, or add some notes for yourself. It's not recommended to change the source or mod type as these control how mods are handled internally.

### Profiles

Just like any other Vortex game, you can have multiple profiles configured for different mod selections. Don't want your streaming mods enabled when you're offline? Set up two profiles and switch over when you're playing with an audience. You can create a new profile from the Profiles screen by either cloning your exising one (from the Edit dropdown menu), or clicking *Add "Beat Saber" Profile*.

> Please note that one-click installs will only be enabled at startup if the *current* profile has it enabled in the profile settings.

### Removing or resetting BeatVortex

If you want to completely reset BeatVortex so that you can start over from scratch, first uninstall all your currently installed mods from the Mods list. Once you've done that (and deployed!) jump to the Profiles screen, and choose *Remove* from the dropdown menu beside the edit button for the "**Beat Saber - Default**" profile. This will effectively reset your Vortex so that Beat Saber will reappear as an available, unmanaged game in the Games list.

To remove BeatVortex entirely, you should uninstall and remove all your installed mods from the Mods list first. After deploying, you can then remove the Default profile (see above), and finally uninstall the extension itself by clicking over to the Extensions screen. BeatVortex will appear near the end of the list as "**Game: Beat Saber**". Click Remove to uninstall BeatVortex.

> Note that Beat Saber will still show up in your Games list since Vortex can redownload the extension from Nexus Mods.

### Purging to default

If you want to take your game back to a default, unmodded state, you can use Vortex's *Purge* feature. Click the Purge Mods button from the Mods list and Vortex will undeploy all your enabled mods, leaving your game directory essentially unmodded. 

> You should be prompted to revert BSIPA patching when you purge, and prompted to rerun patching when you next deploy mods.