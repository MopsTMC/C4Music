# C4Music

C4Music is a lightweight resource pack that satisfyingly completes Minecraft's soundtrack with C418's unused music from Minecraft Volumes [Alpha](https://c418.bandcamp.com/album/minecraft-volume-alpha) & [Beta](https://c418.bandcamp.com/album/minecraft-volume-beta). It removes the music added in Caves & Cliffs, The Wild Update, and Trails & Tales and expands upon the original soundtrack with a faithful approach to the gameplay and its history.

## Thank you for 50k downloads!
I ask you to spare a few minutes to answer the survey below. Your time is helpful and greatly appreciated! <br>
[https://forms.gle/SDwFRtbASJw3Fwov7](https://forms.gle/SDwFRtbASJw3Fwov7)

## Why?

**tl;dr** <br>
In honor of preserving the original soundtrack. If you prefer it too, give this pack a try!
<p>
The Nether Update took an incredible path in music and this was my expectation going into 1.17. The new soundtrack was very exciting even though it got repetitive, constantly being played in the menus and exclusively in the new biomes.
</p>
<p>
Turns out this was somewhat intentional. The original soundtrack is being phased out by music licensed and owned exclusively by Microsoft, even though there's still a bunch of music C418 composed for Minecraft way back that has never officially made an appearance in the game. This is finally its time to shine!
</p>


## Features

- **Gameplay Music**
(Check out this [changelog](https://modrinth.com/resourcepack/c4music/version/2.0) for details)

  - __Removed__: <br>
Stand Tall, Left to Bloom, Wending, Infinite Amethyst, One More Day, Floating Dream, Comforting Memories, An Ordinary Day, Firebugs, Aerie, Labyrinthine, Echo in the Wind, A Familiar Room, Bromelaid, Crescent Dunes

  - __Added__: <br>
Intro, Kyoto, Équinoxe, Ki, Chris, Flake, Excuse, Door, Droopy Likes Ricochet, Beginning, Moog City, Swarms, Peanuts

- **Lightweight** thanks to Packsquash

- Built-in **Mod Support** for [Now Playing](https://modrinth.com/mod/now-playing), [Music Identifier](https://modrinth.com/mod/music-identifier) and [Music Control](https://modrinth.com/mod/music-control)

- **Extras**
  - [Nether Addon](https://modrinth.com/resourcepack/c4music/version/c4nether) - Replaces everything Nether-related
  - [Music Discs](https://modrinth.com/resourcepack/c4music/version/c4records) - Replaces the new records with C418 tracks

## Compatibility

- ### Resource Packs <br>
  C4Music is incompatible with other music-overriding resource packs which provide their own `sounds.json`, such as [Only C418](https://modrinth.com/resourcepack/only-c418). Priority will be given based on placement in the list of the resource pack menu, with an almost guarantee of an inconsistent state. I recommend choosing only one such resource pack to be used at a time.

  To use C4Music alongside resource packs that *add* to the vanilla soundtrack and are known to *not* use the `replace` feature in `sounds.json`, **place C4Music below any such pack** to ensure all tracks are registered.

  Minecraft's warning that the resource pack is made for an older or newer version can be safely ignored as long as the modrinth download page lists your Minecraft version as supported. This is only because it has its pack format set to 9 but it should work on all 1.17+ versions.

- ### Mods <br>
  - ❕ **Mods with built-in resource packs**. These cases should be treated as mentioned above like any other resource pack
  - ✅ **Content mods** usually append to the game's soundtrack with their own sound events so there shouldn't be any issues. However, if a mod is used to replace or modify music, chances are it's going to ignore C4Music
  - ✅ [Start the Music!](https://modrinth.com/mod/start-the-music) is compatible. The same probably goes for [More Music](https://modrinth.com/mod/moremusic)
  - ✅ [Mixtape](https://modrinth.com/mod/mixtape/) works well out of the box with C4Music. There is a rare case though in which creative music will play in survival while using this mod in multiplayer
  - ❌ [Music Notification](https://modrinth.com/mod/music-notification) does not display track info correctly due to the way it parses music and does not allow overrides with resource packs
  - ❌ [Playlist](https://modrinth.com/mod/playlist) is in a grey area, as it undoes the removal part of C4Music. This means its tracks will still play naturally but alongside the new tracks. Also, they are currently not available in its menu but this is a planned feature as mentioned [in this issue](https://github.com/fudgeu/playlist/issues/39)

- ### Bedrock
  ❌ Due to technical complications, bedrock is not supported.

## Notes

- The release channel in every release specifies the amount of testing it has gone through and the extent of its functionality. Issue reporting and feedback are greatly encouraged through [GitHub issues](https://github.com/MopsTMC/C4Music/issues) or Discord `@mopstmc`
  - 🟢 **Release**: Recommended for download; there are no known issues
  - 🟠 **Beta**: In testing; working for the most part but not yet confirmed to be stable
  - 🔴 **Alpha**: Under development; proceed with caution and report any findings if possible as it would help immensely. Old versions tagged as alpha contain bugs and are kept only for archival reasons
- I did not remove any of The Nether Update's soundtrack but rather expanded it and balanced its weight due to it playing a big part in its biomes' ambiance and character.
- I do not wish to belittle the work of Lena Raine, Kumi Tanioka and Aaron Cherof. Their tracks are amazing in their own ways. However, I don't necessarily find them appropriate for Minecraft, especially since they have acted as a replacement rather than an expansion to the existing soundtrack.
- Since July 2023 extraction protection methods have been enforced to abide by [C418's usage policy](https://c418.org/2017/01/26/what-am-i-allowed-to-do-with-daniels-music/) and as such, old versions are no longer available and new ones are not meant to be tampered with. The project's structure is available on GitHub and I plan on providing instructions on how to modify and make addons for it yourself
- **Redistribution without linking back to this page and credit to me and C418 is strictly prohibited**. Apart from that you may freely use this resource pack in any creation and if you wish to share it, make sure to link to this original page

<hr>
<p>

This pack is dedicated to fans of Minecraft and [C418](https://c418.org/)'s amazing work. Credits go to him for the music used in this resource pack
</p>

-----------------------------------------------------------------------------

# Versions

## v4 - Anniversary Update 🥳

It has been 2 years since the first public release of C4Music! Thank you so much for downloading the resource pack, especially to the those who have stuck around since the humble beginnings.

- Added **3 new tracks**

| Track | Album | Plays in |
| :---: | :---: | :---: |
| [peanuts](https://c418.bandcamp.com/track/peanuts) |  little things | Lush Biomes |
| [swarms](https://c418.bandcamp.com/track/swarms) | one | Mountains |
| [mau5cave](https://c418.bandcamp.com/track/mau5cave) | seven years of server data | Caves |

- Each biome now has a **unique tracklist** in order to keep parity with vanilla
- Adjusted **volume** of some tracks
- Added out-of-tune nether tracks as distant echoes in Deep Dark
<details><summary>Click here to view a detailed list of changes</summary>
  <p>

  | Track | Biomes | Volume |
  | :---: | :---: | :---: |
  | Chris | Overworld | -15% |
  | Door | Overworld | -10% |
  | Equinoxe | Overworld, Caves | - |
  | Kyoto | Overworld, Caves | -15% |
  | Droopy | Overworld | -10% | 
  | Peanuts | Flower Forest, Cherry Grove, Lush Caves | -80% |
  | Swarms | Frozen/Stony/Jagged Peaks and Badlands | -75% |
  | Mau5cave | Deep Dark, Dripstone/Lush Caves | -40% |
  | Concrete Halls | Nether, Deep Dark | - |
  | Ballad of the Cats | Nether, Deep Dark | - |
  
  </p>
</details>

<!---
  - https://archive.org/download/MCCOST (halloween)
--->

## 1.20.5+ Compatibility

Due to an oversight with the pack overlay system and some undocumented changes in 1.20.5, the previous version would not register the correct tracklist. This version has only been tested on 1.20.6.

### Changes:
- Pack will no longer catastrophically ruin the tracklist of versions outside of the supported pack formats
- Added compatibility with Now Playing v1.5.1
- **The file can no longer, and is not meant to, be extracted and used outside of the game. It is also [incompatible with Java 22!](https://github.com/MopsTMC/C4Music/issues/5)**

## 1.20.3 Patch

### DO NOT USE IN 1.20.5+
_This version will not play music correctly on versions other than the ones mentioned below_

This release adds compatibility with the path changes in 1.20.3 (pack format 19) and utilises the new pack overlay system for backwards compatibility. _If you are playing on versions earlier than 1.20.3 there is no reason to update, there has been no change in functionality._

### Changes:

- Pack format updated to 18 (1.20.2)
- Supported formats 9-22 (1.19-1.20.4)

These changes only affect versions which can interpret the respective fields in `pack.mcmeta` (>1.20.2) which means minecraft will still complain about the resourcepack being made for an older or newer version depending on your setup. <br>
As for every new release, please report any findings and issues

## Third Major Release

- Fixed the unspecified `flower_forest` and `forest` sound events from the compatibility addon
- The new sound events added in 23w17a inherit from the common `music.game` sound event
- Added compatibility for [Music Identifier](https://modrinth.com/mod/music-identifier) and [Music Control](https://modrinth.com/mod/music-control)
- Music discs are no longer provided in the main resource pack. This functionality has been moved to the [C4Discs](https://modrinth.com/resourcepack/c4music/version/c4discs) addon. I recommend downloading it too for the full experience

**There is no need to use the C4TrailsNTales compatibility addon anymore. If you are on 1.20.3+ download v3.1 of the pack.**

-----------------------------------------------------------------------------

## Now Playing Compatibility

This update brings integration with [Now Playing](https://modrinth.com/mod/eNF4Bfla) which will now show the added tracks' names in its notification. Vanilla Minecraft will probably ignore this version's extra assets but in the rare occassion you have trouble using this resource pack try [the older version](https://modrinth.com/resourcepack/c4music/version/5sNysEA2).

-----------------------------------------------------------------------------

## Major Refactor

This release has brought some much needed polish to C4Music. Its approach has borrowed ideas from [Balanced Music](https://modrinth.com/resourcepack/CWBlLg2t) and their mutual use is now obsolete.
<hr>

**I recommend downloading [the latest version](https://modrinth.com/resourcepack/c4music/version/ZxxqNX0O) of the resource pack which provides better compatibility with mods and other resource packs.** If you want to know more head to the [changelog](https://modrinth.com/resourcepack/c4music/changelog)

### Changes:

- **Disabled New Music** The new music has been disabled through the use of the `replace` feature in `sounds.json` instead of being overwritten. This means that any resource packs' music placed below C4Music will be ignored. To avoid this, move it to the bottom of your resource packs list

- **Balance** All tracks' weights are now equal with some exceptions. This means the music is now mostly equal, regardless of (Overworld) biomes, in chance of playing.

- **Menu** The title screen now features only original menu music

- **Fixed Volume Issues** Some glaring volume balance issues have been fixed and the music now matches the volume of the rest of the soundtrack so you won't have a heartattack when Droopy comes for a friendly visit

- **Track Changes**  No music has been added or removed, rather it has been shifted around with some tracks moving into more appropriate scenarios

- **Nether Music Adjustments** The music from 1.16 "The Nether Update" has been brightened up a little. The original Nether soundtrack can now play in Warped Forests

<details><summary>Click here to view a detailed list of changes</summary>
  <p>

  | Track | Previously Replaced | Plays In | New Identifier | Volume |
  | :---: | :---: | :---: | :---: | :---: |
  | Ki | Infinite Amethyst | End | end/ki | -30% |
  | Intro | Stand Tall | End | end/intro | -30% |
  | Chris | One More Day | Overworld | hal5 | -30% |
  | Door | An Ordinary Day | Overworld | nuance3 | -40% |
  | Équinoxe | Wending | Overworld | nuance4 | -40% |
  | Kyoto | Left to Bloom | Overworld | piano4 | -40% |
  | Droopy Likes Ricochet | Firebugs | Overworld: Meadow | droopy | -50% |
  | Moog City | Labyrinthine | Menu | menu/menu5 | -40% |
  | Beggining | Aerie | Menu | menu/menu6 | -30% |
  | Excuse | Comforting Memories | Nether | nether/nether5 | -25% |
  | Flake | Floating Dream | Nether | nether/nether6 | -25% |
  | Crysopoeia | | Nether | | +15% |
  | So Below | | Nether | | +10% |
  | Eleven | 11 | Jukebox | records/eleven | -5% |
  | Dog | Otherside | Jukebox | records/dog | -5% |

  </p>
</details>

-----------------------------------------------------------------------------

## Initial release

### Gameplay Music Changed
- Stand Tall -> Intro
- Left to Bloom -> Kyoto
- Wending -> Équinoxe
- Infinite Amethyst -> Ki
- One More Day -> Chris
- Floating Dream -> Flake
- Comforting Memories -> Excuse
- An Ordinary Day -> Door
- Firebugs -> Droopy Likes Ricochet
- Aerie -> Beginning
- Labyrinthine -> Moog City

This version of the resource pack does not change the frequency or chance (weight) of a certain song playing. It merely overrides the new sound files so it is expected that they will share frequency and volume. However, their duration on average is shorter so you'll get to listen to more tracks (hopefully) with less repetitiveness. 

## _**The succeeding releases fix all these issues and much more**_
The pack is still usable but I highly suggest downloading the latest version

<hr>
