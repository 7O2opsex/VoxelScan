# VoxelScan 1.4.0

**vibe coded**

Client-side Fabric mod for **Minecraft Java Edition 26.2**. Scans a rectangular 3D volume around the player, measured in **blocks** (not chunks), with independent X / Y / Z radii, and shows the distribution as a donut chart you can read in one glance.

No key is assigned by the mod. Bind **Open VoxelScan** and **Open VoxelScan settings** yourself in **Options → Controls → VoxelScan**. Sodium lists the same category.

## What it answers

> What blocks are present around me, and in what quantities?

Default radius `5 / 5 / 5` covers `11 × 11 × 11 = 1,331` block positions centered on the player.

ESP (off by default) draws through-wall boxes on beds, shulker boxes, chests, ender chests, barrels and spawners that are already in loaded chunks. It never requests chunks.

See `UPDATEV1.0` for everything that changed in 1.1.0.

## Install

1. Install [Minecraft 26.2](https://www.minecraft.net/).
2. Install [Fabric Loader 0.19.3+](https://fabricmc.net/use/) for 26.2.
3. Install [Fabric API](https://modrinth.com/mod/fabric-api) for 26.2.
4. Drop `VoxelScan-1.4.0.jar` into the `mods` folder.

The installable jar is `build/libs/VoxelScan-1.4.0.jar`.

## License

MIT

---
**vibe coded**
