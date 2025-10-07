# Loadout releases (ldtrlss)

[Discord](https://discord.gg/6wyB4zSEsR)

This repository only contains binary releases. Source code is not included.

- [About Gear Score](#about-gear-score)
	- [Weapon Count](#weapon-count)
	- [Score Colors](#score-colors)
- [Overview](#overview)
	- [Windows](#windows)
	- [Floating Gear Score](#floating-gear-score)
	- [Quick Access Menu](#quick-access-menu)
	- [Compact (nested) options](#compact-nested-options)


# About Gear Score
The displayed "gearscore" is made up of two components: Gear Score and Upgrade Score

Gear Score ranges between 0 and 100 and 106.
100 is the reference value meaning a fully exotic set with all stats selected.
106 on the other hand is ascended, the 6 bonus points refer to the percentual stat increase.
When no stats are selected the gear score does not increase, as no stats are gained. (Defense is ignored.)

Upgrade Score ranges between 0 and 100.
100 is the reference value meaning exotic (or above) sigils/runes were equipped, as well as a relic.
For the runes the synergy is also checked.
Meaning that having 4 matching runes and 2 other matching runes increases the gearscore, but not as much as 6 matching ones would.


## Weapon Count
Since builds can have a different amount of weapons, it is only checked how many *should* be equipped compared to the actual equipped ones.
As such, having only one one-handed weapon, means you *should* have (at least) two. The score is calculated based on two.
Equally if an elementalist or engineer has a second set, both sets are factored into the score, if a second set is used.


## Score Colors
Basic. Score below or equal 124
Fine. Score above 124
Masterwork. Score above 139
Rare. Score above 155
Exotic. Score above 177
Ascended. Score above 200
Legendary. Perfect score. (206)

The score is calculated based on a fully geared character with equipment of the equivalent rarity at level 80.
Exotic. Score above 177
Ascended. Score above 200
Legendary. Perfect score. (206)

# Overview
## Windows
On the left the seperately selectable windows, on the right compact window can be anchored to other windows when `Edit Layout` is checked.
<img width="1211" height="830" alt="overview" src="https://github.com/user-attachments/assets/e690eca2-3e96-4672-bc89-c79afba38df7" />

## Floating Gear Score
Displays gear score numbers on players, color based on score.
<img width="1019" height="601" alt="floating" src="https://github.com/user-attachments/assets/136c20a8-f5ef-4700-972c-4a783ed5fc03" />

## Quick Access Menu
Quickly enable/disable windows or settings
<img width="1157" height="719" alt="quick-menu" src="https://github.com/user-attachments/assets/18667e5b-35fd-42d1-8b13-56c13634c3a7" />

## Compact (nested) options
The compact window has some nested options to customize what shows up in there
<img width="686" height="360" alt="compact-options" src="https://github.com/user-attachments/assets/9c29997e-1dbb-4d6c-ab67-4e768a335281" />
