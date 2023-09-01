# C4Music

C4Music is a resource pack that removes the music added in the Caves and Cliffs Update & The Wild Update and expands upon the original soundtrack with [C418's](https://c418.org/) unused music from Minecraft Volumes [Alpha](https://c418.bandcamp.com/album/minecraft-volume-alpha) & [Beta](https://c418.bandcamp.com/album/minecraft-volume-beta) with a faithful approach to the gameplay and its history.

## Why?
<p>
With the first update to 1.17, I was greeted with some awesome new music. It was a breath of fresh air to hear something new after such a long time of playing the game, especially with the incredible path the Nether Update followed in terms of acoustics. <br>
It wouldn't take long, however, to realize how rare it would be that I heard music by C418. Every time I launched the game I would hear the newly added music instead and it got uncanny.
</p>
<p>
It seems like for every version from 1.17 upwards the original soundtrack is being pushed to a progressively further back seat and as the new soundtrack was monotonously prevailing, I started missing the nostalgic melodies of Mincraft's infamous soundtrack and wanted to preserve them in some way.
</p>
<p>
There's still a bunch of music C418 composed for Minecraft way back that has never made an appearance in the game though and it is its time to shine.
</p>

### tl;dr
I find the music by C418 more faithful to the game and enjoy its presence more than the new soundtracks. <br>
If you do too, give this pack a try

## Changes

### Gameplay Music
(Check out this [changelog](https://modrinth.com/resourcepack/c4music/version/2.0) for details)

- __Removed__: <br>
Stand Tall, Left to Bloom, Wending, Infinite Amethyst, One More Day, Floating Dream, Comforting Memories, An Ordinary Day, Firebugs, Aerie, Labyrinthine

- __Added__: <br>
Intro, Kyoto, Équinoxe, Ki, Chris, Flake, Excuse, Door, Droopy Likes Ricochet, Beginning, Moog City

- __No biome-specific tracks__ Most tracks will play wherever you are


### Extras
- [Nether Addon](https://modrinth.com/resourcepack/c4music/version/c4nether) - Replaces everything Nether-related
- [Music Discs](https://modrinth.com/resourcepack/c4music/version/c4records) - Replaces the new records with some better choices

## Compatibility

- ### Resource Packs <br>
  C4Music is incompatible with other music-overriding resource packs which provide their own `sounds.json`, such as [Only C418](https://modrinth.com/resourcepack/only-c418). Priority will be given based on placement in the list of the resource pack menu, with an almost guarantee of an inconsistent state. I recommend chosing only one such resource pack to be used at a given time.

  To use C4Music alongside resource packs that *add* to the vanilla soundtrack and are known to *not* use the `replace` feature in `sounds.json`, place C4Music below any such pack to ensure all tracks are registered.

  Keep in mind that resource packs that change the translation strings and/or textures of records may also interfere with that part of C4Music. There are some cases where in modded instances, record descriptions will be shown incorrectly. You'll need a bit of fiddling around to find the resource pack order that prevents this.

- ### Mods <br>
  - ❕ **Mods which utilise built-in resource packs**. These cases should be treated as mentioned above like any other resource pack
  - ✅ **Content mods** usually append to the game's soundtrack so there shouldn't be any issues. However, if a mod is used to replace or modify music, chances are it's going to ignore C4Music
  - ✅ [Start the Music!](https://modrinth.com/mod/start-the-music) is compatible. Same probably goes for [More Music](https://modrinth.com/mod/moremusic)
  - ✅ [Mixtape](https://modrinth.com/mod/mixtape/) works well out of the box with C4Music. There is a rare case though in which creative music will play in survival while using this mod on multiplayer
  - ✅ Starting with v2.2, there's an integration with [Now Playing](https://modrinth.com/mod/now-playing)
  - ✅ The third major release (v3.0) provides support for [Music Identifier](https://modrinth.com/mod/music-identifier) and [Music Control](https://modrinth.com/mod/music-control)
  - ❌ [Music Notification](https://modrinth.com/mod/music-notification) does not display track info correctly due to the way it parses music and does not allow overrides with resource packs
  - ❌ [Playlist](https://modrinth.com/mod/playlist) is in a grey area, as it undoes the removal part of C4Music. This means its tracks will still play naturally but alongside the new tracks. Also, they are currently not available in its menu but this is a planned feature as mentioned [in this issue](https://github.com/fudgeu/playlist/issues/39)

- ### Bedrock Support
  ❌ Due to complexity, bedrock support will not be provided, at least not in the near future.

## Related projects
- If you are familiar with fabric mods, you should definitely check out [Mixtape](https://modrinth.com/mod/mixtape/) with similar funtionality, more features and configurability
- If instead you'd like to keep the new music but have it play in a more balanced manner, try out the [Balanced Music](https://modrinth.com/resourcepack/balanced-music) resource pack
- [Biome Music Unlocker](https://modrinth.com/resourcepack/biome-music-unlocker) is a simple resource pack that adds the ability for biome-specific tracks to play in pre-1.17 biomes
- There are also [Minecraft Music Revised](https://modrinth.com/resourcepack/minecraft-music-revised) and [More C418 Music](https://modrinth.com/resourcepack/more-c418-music) which rid the game off  any non-C418 music entirely, albeit with some more subjective tweaks and heavier edits

## Notes

- The release channel in every release specifies the amount of testing it has gone through and the extense of its functionality:
  - 🟢 **Release**: Recommended for download; there are no known issues
  - 🟠 **Beta**: In testing; working for the most part but not yet confirmed to be stable
  - 🔴 **Alpha**: Under development; proceed with caution and report any findings if possible as it would help immensly. Old versions tagged as alpha contain bugs and are kept only for archival reasons
- Minecraft's warning that the resource pack is made for an older or newer version can be safely ignored. This is only because it has its pack format set to 9 but it should work on all 1.17+ versions. Tested on: 1.19.2, 1.18.2
- I have left anything related to the Deep Dark (Ancestry & 5) untouched as I consider it part of the game progression, story-telling and ambiance. For the same reason I did not remove any of The Nether Update's soundtrack, which accompanied the new biomes, but rather expanded it and balanced its weight.
- I do not wish to belittle Lena Raine's and Kumi Tanioka's work. Their scores are amazing in their own ways. However, I don't necessarily find them appropriate for Minecraft, especially since they have acted as a replacement rather than an expansion to the existing soundtrack.
- There are plenty of resource packs which add C418 music to Minecraft from other albums too. My goal for this resource pack was not that as:
  1. There are too many good songs to chose from, as are the combinations
  2. I wanted to stick to what was intended/proposed for Minecraft (Volumes Alpha & Beta).
  3. It's difficult to find a configuration that would satisfy a big enough audience. There are countless tracklists/resource packs that could be created and everyone has their own preferences. The best solution for this is for me to "open source" the project and provide intructions on how to modify it yourself, something I'm planning for the future, so there will be no need to scour the internet and forcefully abide by others' tastes. <br>
  This is why I'm mostly negative towards "personalised" resource packs which are very opinionated and do not serve much purpose
- Since July 2023 extraction protection methods have been enforced in order to abide by [C418's usage policy](https://c418.org/2017/01/26/what-am-i-allowed-to-do-with-daniels-music/) and as such, old versions are no longer available
- **Redistribution without linking back to this page and credit to me and C418 is strictly prohibited**. Apart from that you may freely use this resource pack in any creation and if you wish to share it, make sure to link to this original page

<hr>
<p>
This pack is dedicated to fans of Minecraft and C418's amazing work. Credits go to him for the music used in this resource pack
</p>
<p>

For issue reporting, feedback and support, please don't hesitate to contact me on Discord: [MopsTMC#3659](https://discord.com/users/449838723371237387)

</p>

-----------------------------------------------------------------------------

# Versions

## Third Major Release

- Fixed the unspecified `flower_forest` and `forest` sound events from the compatibility addon
- The new sound events added in 23w17a inherit from the common `music.game` sound event
- Added compatibility for [Music Identifier](https://modrinth.com/mod/music-identifier) and [Music Control](https://modrinth.com/mod/music-control)
- Music discs are no longer provided in the main resource pack. This functionality has been moved to the [C4Discs](https://modrinth.com/resourcepack/c4music/version/c4discs) addon. I recommend downloading it too for the full experience

### There is no need to use the C4TrailsNTales compatibility addon anymore
As for every new release, please report any findings and issues

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