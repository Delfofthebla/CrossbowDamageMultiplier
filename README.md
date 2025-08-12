# CrossbowDamageMultiplier

A Synthesis patcher for Skyrim that can increase (or reduce) damage dealt by crossbow weapons.

### Justification

When trying to play a crossbow focused character with mods that added a large number of new crossbows, and combining it with the [Non-Exploitable Crossbow Reloading SE](https://www.nexusmods.com/skyrimspecialedition/mods/29869) mod, I found that there was truly no good reason to use a crossbow. Bows were just...better. It didn't matter what tier it was, I was wasting my time due to the reloading requirement. But that was supposed to be part of the fun. You take careful, deliberate shots, and deal big damage!

...Except there wasn't any.

Instead of making a million patches for each and every crossbow mod in the world, I decided to just write a synthesis patcher that could give a % boost to each crossbow. Simply set your multiplier (defaults to 30%), and enjoy.

The settings allow the user to provide a list of mod names and/or EditorIDs to ignore. Mod name is matched against the mod where the record was first introduced (i.e., skyrim.esm would ignore all spells from the original vanilla game, but not those added in DLCs).
