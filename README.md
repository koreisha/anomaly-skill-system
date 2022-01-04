# Anomaly Skill System
This addon adds skills with leveling to anomaly.
In total there's 4 skills:

## Strength:
Levels are gained for traveling with heavy loads.\
Grants: increased carry weight and melee damage.

## Endurance:
Levels are gained by traveling light.\
Grants: increased stamina and speed.

## Scavenging:
Levels are gained by looting stalkers.\
Grants: increased drops from stalkers.

## Survival:
Levels are gained by taking physical damage and skinning mutants.\
Grants: increased damage resistance and chance to get extra part when looting mutants.

Player starts with decrease in these respective stats, so start of the game is harder.\
Stats can be checked by pressing K to open skills menu

# Changelog:
- 20-11-2021 - Release
- 25-11-2021 - hotfix for bleeding and integration of UI script edit by demonized (now it opens and closes with the same button as well as ESC)
- 26-11-2021 - actual fix for bleeding, added ru localization for title in skills menu
- 02-12-2021 - changed how stats are stored and incremented (would make adding new features easier in the future for me and other people), fixed some others erros in the code, fixed speed (finally), fix for crash on localizations other than ru\eng.
- 21-12-2021 - rebalanced scavenging (fixed the way drops were added, increased exp gained for kills), rebalanced survival and added exp gain for killing mutants, also leveling survival now adds a chance to gain additional part when skinning, when it's survival is low you have chance to lose some parts.
- 04-01-2022 - added support for MCM keybinds, reworked scavenging exp gain, now it's gained for looting stalkers