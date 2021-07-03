# Realms Beyond

Endgame worlds to quickly scour, loot and forget, heavily inspired by the Path of Exile map device. Mostly meant to provide scalable content to put your endgame gear in use.

## The portal device

After defeating the Ender Dragon, the central monolith of the generated portal can be interacted with to open up the portal device's interface. The central four slots are where you assemble keystones, while the nine slots below serve for offerings. #TODO are player-built portal devices

## Keystone

Four matching keystones are used to open a portal. All four keystones can be enchanted, and their enchantment levels are added up for the final portal. Enchantments can alter the destination's properties in a way similar to offerings, or enhance the strength of offerings. Portals only last for five minutes, after which return is not possible.

Currently considered keystone enchantments:
* Divine Favor I-III: +10% offering effect (Max: +120%)
* Way of Steel I-III: +50% monster damage, +3% quantity (Max: +600%, +36%)
* Way of Flesh I-III: +50% monster health, +3% quantity (Max: +600%, +36%)
* Sands of Time I-III: +30s realm lifespan (Max: +6min)

## Realm

A portal leads to a realm with properties defined by the realm's type as well as modifiers from enchantments, offerings or possibly other sources. Base type values are multiplicative with modifiers from other sources, which then are additive with each other unless stated otherwise. Realms only last for twenty minutes, after which players are forcefully teleported out.

## Offerings

Different items can be used to alter the destination's properties. Offerings stack as far as item in question allows. Currently considered offerings include:
* Rotten flesh: +5% monster health, +0.3% quantity (Stack: +320%, +19.2%)
* Bone: +5% monster damage, +0.3% quantity (Stack: +320%, +19.2%)
* Spider eye: players take +0.5 magic damage every 5 seconds, +0.3% quantity (Stack: +32, +19.2%)
* Iron ingot: +0.5 monster armor, +0.1 monster armor toughness, +0.3% quantity (Stack: +32, +6.4, +19.2%)
* String: -0.5% player movement speed, +0.2% quantity (Stack: -32%, +12.8%)
* Feather: +0.5% monster movement speed, +0.2% quantity (Stack: +32%, +12.8%)
* Sand: +10s realm lifespan (Stack: +6min 40s)
* Ender pearl: +40s portal lifespan (Stack: +6min 40s)
* Diamond ore: +0.5% ore veins spawn (Stack: +32%)

## Quantity

Quantity is implemented through rolling loot tables for monster drops and chests multiple times, for example with quantity 230% an opened dungeon chest will contain the result of two dungeon loot table rolls, plus 30% chance for an additional one.
