# retro-lan

an easy way to install and run classic pc games for a quick lan with friends.

you bring your own copy of each game. this repo never hosts game files.

## what it will do

- find your existing installs (steam, gog, or pick a folder)
- fetch official patches and community engines from their original sources, hash checked
- apply the tweaks needed to run on windows 11
- set up lan play, same network first, remote play later
- one simple gui for all of it

## status

planning, nothing is built yet.

- windows 11 first
- linux later, using proton where needed
- macos maybe after that

## games

| game | what we use | source |
| --- | --- | --- |
| unreal tournament 99 | oldunreal 469 patch | https://github.com/OldUnreal/UnrealTournamentPatches |
| unreal tournament 2004 | oldunreal patches | https://github.com/OldUnreal/UT2004Patches |
| generals and zero hour | generalsgamecode weekly builds | https://github.com/TheSuperHackers/GeneralsGameCode |
| red alert 1 and tiberian dawn | openra | https://github.com/OpenRA/OpenRA |
| red alert 2 and yuri's revenge | cncnet client and yr package | https://github.com/CnCNet/cncnet-yr-client-package |

more later.

## sources

- ea generals and zero hour source release: https://github.com/electronicarts/CnC_Generals_Zero_Hour
- generalsx, native linux and macos port of generals: https://github.com/fbraz3/GeneralsX
- surrealengine, ut99 engine rewrite, not playable enough yet: https://github.com/dpjudas/SurrealEngine
- cnc-ddraw, display fixes for old games on windows 10 and 11: https://github.com/FunkyFr3sh/cnc-ddraw
- cncnet client: https://github.com/CnCNet/xna-cncnet-client
- n2n, layer 2 vpn we are looking at for remote lan: https://github.com/ntop/n2n

## patches

we only use official or well known community patches, linked above. if we ever carry our own they go in `patches/` with a note on what they change and where they came from.

## rules

- no game files, no cracks, no no-cd patches
- everything is fetched from its original source onto your machine
- not affiliated with any publisher, all game names belong to their owners

## license

mit
