# Godzilla: The Run (7 Days to Die mod)

*A free, unofficial, non-commercial fan mod. Godzilla is a trademark of Toho Co., Ltd.; this mod is not affiliated with or endorsed by Toho.*

Godzilla has come ashore. You can't fight him. You run.

A single player survival run across a custom world: five biome strips stacked north to south (pine forest, burnt forest, desert, snow, wasteland), joined by one road and one mountain pass between each strip. Radiation spreads behind you between blood moons, the dead it touches get back up, and every blood moon you need to be somewhere high and safe. Along the way, traders know where the army left its gear.

Follow the order from the Disaster Response Bureau in your starting note. It tells you everything you need to know to begin.

## Requirements

- 7 Days to Die **V3.3** (built and tested on V3.3 b17), PC.
- **Single player only.** In hosted or dedicated games the event switches itself off.
- **Launch without EasyAntiCheat.** The mod runs code (a DLL), so EAC has to be off: in the game launcher untick "Use EAC", or start `7DaysToDie.exe` directly.
- A new game on the **Godzilla** world that comes with the mod. Other worlds load fine, but The Run only starts on this one.

## Install

1. Unzip. You get a `KaijuMod` folder plus this README, CREDITS.txt and LICENSE.
2. Copy the `KaijuMod` folder into `<7 Days to Die install>\Mods\`, e.g. `C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods\KaijuMod`. (Create the `Mods` folder if it isn't there.)
3. Start the game without EAC.

The world is inside the mod (`KaijuMod\Worlds\Godzilla`); the game finds it there, so there's nothing to copy into GeneratedWorlds.

## Starting a run

1. New Game, mode Survival (single player).
2. World: **Godzilla**.
3. Any game name and difficulty you like. Any blood moon frequency works; the run is paced on it, one biome per blood moon.
4. Start, and read your note.

Tips: keep moving east at first, and keep an eye on the western sky. The army posts on the mountain shelves above the big cities make good places to sit out a blood moon, and their towers are built to be fortified. The further you go, the bigger they get, and the later ones go a long way underground. Look around the top of each tower: the army left something there that helps against his radiation.

## Console commands

Open the console with F1. `kaiju help` lists everything.

Everyday:
- `kaiju version`: the mod's version.
- `kaiju run`: day, strip and how far the radiation has come.
- `kaiju parts`: the army gear you've found and still need.
- `kaiju scales`: the G-scales you're wearing and how much of his radiation they turn aside.
- `kaiju perf`: what the mod costs per frame, by subsystem; `kaiju perf off <name>` to switch a part off and compare.
- `kaiju zbreath off` / `kaiju zblast off`: turn off the irradiated zombies' ranged spit or their death blasts if you'd rather not have them.
- `kaiju gcell skins off`: plain zombie skins for zombies that spawn from now on.
- `kaiju style classic`: an alternative look for his attacks.

Testing and cheats (spoilers): `kaiju attack`, `kaiju give`, `kaiju gcell`, `kaiju test`, `kaiju breath`, `kaiju roar`, `kaiju radiation off`, `kaiju run reset`. See `kaiju help` for what they do.

## Known limits

- Single player only, and only on the Godzilla world.
- Needs EAC off.
- Overhaul mods that replace the starting note, quests, traders or the world list may conflict.
- He is very big and the effects are heavy; on slower PCs `kaiju perf` shows what to switch off.
- Saves made on one version of the world should be finished on that version: a world update only reaches areas you haven't explored yet.

## Credits and licence

See CREDITS.txt. This is a free, unofficial, non-commercial fan mod. Godzilla is a trademark of Toho Co., Ltd.; this mod is not affiliated with or endorsed by Toho. The mod's code is MIT licensed (LICENSE).
