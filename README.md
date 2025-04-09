# ResourceFinder Mod for Valheim

## Description
**ResourceFinder** is a client-only Valheim mod that allows players to easily locate resources, trees, plants, and items in storage containers using console commands.

### Features:
- **Locate Resource Nodes**: Quickly locate resources like **copper**, **carrot**, **tin**, and more.
- **Locate Items in Storage**: Search containers for specific items in nearby storage.
- **Map Pins**: Display resource pins on the minimap.
- **Floating World Markers**: Display floating text markers for resources found.
- **Customizable**: Toggle map pins and floating markers via config file.

### Installation Instructions:
1. Download the **ResourceFinder.dll** mod file.
2. Place the **ResourceFinder.dll** file into your Valheim's **BepInEx/plugins** folder.
3. Start the game, and the mod will load automatically.

### Console Commands:
- `locate [resource]`: Find the specified resource in the world.
- `locate storage [item]`: Find the specified item in nearby storage containers.
- `locate list`: List all available keywords for resources.

### Configuration:
To toggle the map pins and world markers, open the **BepInEx/config/ResourceFinder.cfg** file and modify the settings:
- `ShowMapPins`: Set to `true` to show map pins for found resources.
- `ShowWorldMarkers`: Set to `true` to show floating world markers for found resources.

## License
This mod is free to use and modify for personal use. Please do not redistribute without permission.
