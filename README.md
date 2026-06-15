# NeonCity - Unciv Mod

A futuristic Unciv civilization mod featuring the NeonCity Core faction with advanced drone technology and resource production.

## Version
**0.1** - Initial Release

## Author
EEee1406

## Features

### 🏙️ Civilization: NeonCity Core
- **Leader:** Neon AI
- **Bonuses:**
  - +2 Science per city
  - +10% Production in all cities
- **Start Bias:** Plains
- **Capital:** Neon Prime
- **Other Cities:** Cyber District, Neon Harbor, Grid-7

### 🤖 Units
- **Neon Drone** - Advanced reconnaissance unit with self-destruct capability
  - Cost: 50
  - Movement: 3
  - Strength: 20
  - Unique: Self-destructs when attacking

### 💰 Resources
- **Neon Energy** - Strategic resource
- **Crypto Shards** - Strategic resource
- **Data Credits** - Strategic resource

## Installation

1. Extract the NeonCity folder to your Unciv mods directory:
   - **Windows:** `Documents\Unciv\mods\`
   - **Mac:** `~/Library/Application Support/Unciv/mods/`
   - **Linux:** `~/.local/share/Unciv/mods/`

2. Launch Unciv and enable the NeonCity mod in the mod selection menu

3. Start a new game and select "NeonCity Core" civilization

## Structure

```
NeonCity/
├─ jsons/
│  ├─ mod.hjson
│  ├─ Nations.json
│  ├─ Units.json
│  ├─ Buildings.json
│  ├─ TileResources.json
│  └─ Translations/
│     └─ en_US.properties
├─ Images/
└─ README.md
```

## Validation

✅ All JSON/HJSON files are valid Unciv format
✅ Only standard Unciv mechanics used
✅ No fictional uniques or mechanics
✅ Ready for expansion with additional content

## Future Expansion

This mod is designed as a foundation for:
- Additional civilizations and leaders
- Custom buildings and improvements
- New technologies and unit types
- Advanced bonuses and mechanics

## Notes

- All uniques use validated Unciv syntax
- Resources are stockpiled strategic resources
- Mod loads without errors in current Unciv version
