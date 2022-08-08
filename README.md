# pf1e-path-of-war
FoundryVTT - Pathfinder 1e - Path of War

This simple module includes compendia for Dreamscarred Press' Path of War, including:
- Classes
- Class Abilities
- Feats
- Maneuvers
- A few helpful macros

## Classes
Included so far are only the standard Path of War classes: Harbinger, Mystic, Stalker, Warder, Warlord, and Zealot. I have not added any archetypes yet.

## Class Abilities
This compendium includes all class abilities for the provided classes. They are already linked to the classes, so they should appear in your character sheet upon level-up.

I've also added all of the abilities for the other martial classes: Primal Disciple, Rubato, Nightmare, Myrmidon, Roil Dancer, Mind's eye Disciple, Monk of the Silver Fist, Knight Disciple, Pathwalker, Ambush Hunter, Hidden Blade, War Soul, Polymath, and Warpath Follower. However, I have not gotten around to adding them as individual classes yet.

I have not added any archetypes or prestige classes, nor their abilities.

I have organized this compendium using [Compendium Folders](https://github.com/earlSt1/vtt-compendium-folders). It is not a necessary module, but it may help make things easier to find (and ensure you don't have artifact entries).

## Feats
This is a simple compendium with entries for each of the Path of War feats. I have not done anything special with them, it is merely their descriptions.

## Maneuvers
Again, this includes entries for each of the options, but I have not done any automation. There is no damage dice rolled, no saving throws asked for, or anything along those lines. Merely the description includes all of that information. I do not intend to update these, other than the ones used in my personal games.

Maneuvers are added as spells, with stances as cantrips.

Compendium Folders is even more useful here, for searching the various disciplines.

## Macros
I have included three macros:
1. **Change Stance** - This macro requires that you have setup buffs inside your character sheet for each of the stances you have. Each *must* include "Stance" in its name. Then, the macro will provide a pop-up where you can select one of the stances, toggling it on and ensuring all others are turned off.
2. **Prepare Stances** - This requires the [Spellcaster Utility for PF1](https://github.com/SvenWerlen/fvtt-spellcaster-utility-pf1) module. It provides a pop-up with all of your known maneuvers, allowing you to select which ones you wish to prepare for the day. By default, it is set to your primary spellbook, but it is easy to change to secondary or tertiary.
3. **Recover All Maneuvers** - Resets ALL maneuvers in your primary (by default) spellbook to their prepared amount (which should only ever be 1 or 0).

---

To-Do: 
- Add core PF martial classes
- Add PoW archetypes
- Add PoW prestige classes
- Create buff compendium for stances
