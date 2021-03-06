l4d2_direct (SM 1.9+)
=====================

This project aims to expose Director and other variables to sourcepawn scripters.

Previously this sort of work was done through left4downtown2, but since Sourcemod 1.4 direct address reads and writes are available directly through sourcepawn.

Ideally, l4d2_direct will provide a simple API for reading and writing to the various CDirector classes, ZombieManager, TerrorNavMesh, and other useful classes.

Code is released under GPLv3 as with every other SourcePawn project.

Changelog
=====================

2.1.1 (09-08-2020)
---------------------
- Added `L4D2Direct_GetGameModeBase` (Linux-only). Allows to get the base game mode of the current `mp_gamemode`.
- Added `L4D2Direct_ResetTeamScores` (props to [LuxLuma](https://github.com/LuxLuma) for Windows signature).
- Added `L4D2Direct_ChangeLevel` (props to [LuxLuma](https://github.com/LuxLuma) for Windows signature).
- Added `L4D2Direct_ChangeMission` (Linux-only). Allows to change campaigns via Director with proper initialization and cleanup.

2.0.0 (08-30-2020)
---------------------
- Includes and test files remade into SourcePawn Transitional Syntax

1.0.0 (02-26-2014)
---------------------
- Last version made by ConfoglTeam.
