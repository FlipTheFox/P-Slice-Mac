# What the hell is this??
Exactly what it sounds like-- P-Slice for mac.

This is NOT official. I am NOT affiliated with mikolka9144, and I am CERTAINLY not associated with anyone on the Psych Engine or Funkin' teams.









# Friday Night Funkin' - P-Slice Engine
This engine was originally meant to be a playground for making Psych Engine compatible with linux, but after some attempts in porting V-Slice content became a crossover between Psych Engine and V-Slice (also known as base game).

# Features

> custom stickers

Mods made for P-Slice now can select which sticker pack and set to use on the next sticker transition.

``setPropertyFromClass("substates.StickerSubState", "STICKER_SET", "sticker-set-1")`` defines which sticker set to use (it's the name of one of the directories in `images/transitionSwag/`)

``setPropertyFromClass("substates.StickerSubState", "STICKER_PACK", "all")`` defines a pack of stickers to use from the current set. If such pack doesn't exist all defined stickers in a ".json" file will be used.

> custom freeplay icons

You can now put V-slice freeplay icons into `images/freeplay/icons/{charId}pixel.png`
