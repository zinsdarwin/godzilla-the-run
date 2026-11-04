# Godzilla: The Run (7 Days to Die mod)

*A free, unofficial, non-commercial fan mod. Godzilla is a trademark of Toho Co., Ltd.; this mod is not affiliated with or endorsed by Toho.*

Godzilla has come ashore. You can't fight him. You run.

Two ways to play:

- **The Run**, on the Godzilla world that comes with the mod: a survival run, alone or together, across a custom world of five biome strips stacked north to south (pine forest, burnt forest, desert, snow, wasteland), joined by one road and one mountain pass between each strip. Radiation spreads behind you between blood moons, the dead it touches get back up, and every blood moon you need to be somewhere high and safe. Along the way, traders know where the army left its gear.
- **Godzilla Anywhere**, on any other map (Navezgane, a pregen or a random world): switch him on in the game's Sandbox Options and he comes for the town you're in or nearest to, after each blood moon or every few days. More below.

## Requirements

- 7 Days to Die **V3.3** (built and tested on V3.3 b17), PC.
- **Single player, co-op or a dedicated server.** In multiplayer everyone needs the mod, the same version, and EAC off (see Multiplayer below).
- **Launch without EasyAntiCheat.** The mod runs code (a DLL), so EAC has to be off: in the game launcher untick "Use EAC", or start `7DaysToDie.exe` directly.

## Install

1. Unzip. You get a `KaijuMod` folder plus this README, CREDITS.txt and LICENSE.
2. Copy the `KaijuMod` folder into `<7 Days to Die install>\Mods\`, e.g. `C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods\KaijuMod`. (Create the `Mods` folder if it isn't there.)
3. Start the game without EAC.

The Godzilla world is inside the mod (`KaijuMod\Worlds\Godzilla`); the game finds it there, so there's nothing to copy into GeneratedWorlds.

## The Run

1. New Game, mode Survival (or host it for friends, or run it on a dedicated server).
2. World: **Godzilla**.
3. Any game name and difficulty you like. Any blood moon frequency works; the run is paced on it, one biome per blood moon.
4. Start, and read your note.

Follow the order from the Disaster Response Bureau in your starting note. It tells you everything you need to know to begin.

Tips: keep moving east at first, and keep an eye on the western sky. The army posts on the mountain shelves above the big cities make good places to sit out a blood moon, and their towers are built to be fortified. The further you go, the bigger they get, and the later ones go a long way underground. Ask the trader in each big city about the post above it: the army left something at the top of its tower that helps against his radiation.

## Godzilla Anywhere

1. New Game on any world other than Godzilla.
2. Open the Sandbox Options and the **Godzilla** tab:
   - **Godzilla Anywhere**: Off (the default), After Blood Moon (the morning after each horde) or Every Few Days.
   - **Godzilla Frequency** and **Godzilla Range**: with Every Few Days, how many days between his visits, plus up to this many more at random (like the blood moon range).
   - **Godzilla Warning**: how long before he comes the ground starts to tremble.
3. Start. When the ground trembles, get out of town.

He comes from the nearest sea or lake if there is one, else overland, levels the town and leaves. The towns he levels stay irradiated, and the dead there get back up as G-cell zombies at night. Traders offer jobs by the biome they stand in: the army's gear (burnt forest, desert, snow and wasteland traders), and the G-scale armor mods that turn his radiation aside (pine forest, burnt forest, desert and snow). Bring a gyrocopter of your own.

**Army posts on random worlds:** a random world generated with the mod installed gets the mod's army posts in its wilderness, each in its own biome, and the G-scale jobs send you to them. Worlds generated before you installed the mod (and Navezgane and the pregens) don't have posts; their G-scale jobs use the game's own military sites instead.

Already in a save? `kaiju anywhere <off|bloodmoon|weekly|every N [range]|warning M|status>` sets it for that save from the console.

## Multiplayer

The host (or the dedicated server) runs Godzilla and the run; everyone else sees him, the breath, the clouds and the fallout on their own screen.

- Everyone needs the mod installed, the same version, and EAC off. The game won't let a player without it join.
- Radiation is per player: each of you takes your own dose, cut by the G-scales you wear, with your own warnings.
- Trader jobs, parts, G-scales and weapons are per player, like the game's own items and quests. Anyone can fire a weapon; everyone sees it.
- Godzilla Anywhere: each warning picks one of you at random, and he comes for the town nearest them. Everyone gets the warning.
- The `kaiju` console commands are for admins. Those about your own game (`scales`, `parts`, `perf`, `gcell skins`...) run on your own game.
- Dedicated server: set Godzilla Anywhere with `kaiju anywhere ...` in the server console or telnet, or with `KaijuModnywhere.xml` (`default="bloodmoon"` or `"every"`). The Run needs the server's world set to Godzilla.
- Known gap: you won't see a G-cell zombie's spit aimed at another player.

## Console commands

Open the console with F1. `kaiju help` lists everything.

Everyday:
- `kaiju version`: the mod's version.
- `kaiju run`: day, strip and how far the radiation has come.
- `kaiju anywhere status`: Godzilla Anywhere's settings for this save and when he comes next.
- `kaiju parts`: the army gear you've found and still need.
- `kaiju scales`: the G-scales you're wearing and how much of his radiation they turn aside.
- `kaiju perf`: what the mod costs per frame, by subsystem; `kaiju perf off <name>` to switch a part off and compare.
- `kaiju zbreath off` / `kaiju zblast off`: turn off the irradiated zombies' ranged spit or their death blasts if you'd rather not have them.
- `kaiju gcell skins off`: plain zombie skins for zombies that spawn from now on.
- `kaiju hatches`: if you updated mid-game, turns the vault hatches of an army post you're standing in to open against the wall.
- `kaiju style classic`: an alternative look for his attacks.

Testing and cheats (spoilers): `kaiju attack`, `kaiju anywhere now`, `kaiju give`, `kaiju gcell`, `kaiju test`, `kaiju breath`, `kaiju roar`, `kaiju radiation off`, `kaiju run reset`. See `kaiju help` for what they do.

## Known limits

- Multiplayer needs the mod on every player's game (same version, EAC off).
- Needs EAC off.
- Overhaul mods that replace the starting note, quests, traders or the world list may conflict.
- He is very big and the effects are heavy; on slower PCs `kaiju perf` shows what to switch off.
- Saves made on one version of the world should be finished on that version: a world update only reaches areas you haven't explored yet.

## Credits and licence

Inspired by Glock9's Ramblin Man (https://www.youtube.com/playlist?list=PLc594J9-WhOzu-wr3p_PN9qW_5mVovAzo) and Guns, Nerds, and Steel's The Road (https://www.youtube.com/playlist?list=PLWh-qD3Q6cxk) series.

See CREDITS.txt. This is a free, unofficial, non-commercial fan mod. Godzilla is a trademark of Toho Co., Ltd.; this mod is not affiliated with or endorsed by Toho. The mod's code is MIT licensed (LICENSE).
