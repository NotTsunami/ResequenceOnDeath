# SequenceOnDeath
A Risk of Rain 2 mod that applies the inventory sequencing of a Shrine of Order on player deaths.

## Features
This mod applies the same inventory sequencing effect that a Shrine of Order applies on a player death, similar to the old [OrderOnDeath](https://thunderstore.io/package/Kintelligence/OrderOnDeath/) mod. You must either be in a multiplayer game OR have a Dio's Best Friend.

## Installation
1. Install [BepInEx](https://thunderstore.io/package/bbepis/BepInExPack/) and [R2API](https://thunderstore.io/package/tristanmcpherson/R2API/).
2. Copy the included `SequenceOnDeath.dll` into the resulting `C:\Program Files (x86)\Steam\steamapps\common\Risk of Rain 2\BepInEx\plugins` folder.
3. Launch the game and enjoy! To remove you simply need to delete the `SequenceOnDeath.dll` file.

## Changelog
### Version 1.0.2
- Build against latest R2API
- Don't sequence on single-player games without a Dio's Best Friend
- Reorder checks to reduce the amount of calls
- Rename to SequenceOnDeath

### Version 1.0.1
- Only apply to players, not monsters