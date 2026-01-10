---
layout: page
permalink: /minecraft
---
Prospero runs a _mostly Vanilla_ Minecraft Java Edition server at the following location:

```
ellcrys.dyndns.org
```

As of writing this, it is running version `1.21.11`. It is a Fabric server with a bunch of mods, a few datapacks, and a custom resourcepack.

## Connecting with Vanilla Minecraft

The server has a whitelist, so you need to be added. Aside from that, you can connect with an unmodded Minecraft client, though you'll miss a few interesting features such as:

- Voice chat
- Custom audio
- The ability to change the pose of armor stands

## Setting up Fabric

If you want to have the full experience, you'll need to install [Fabric](https://fabricmc.net/). You can download the [universal installer](https://fabricmc.net/use/installer/) and it will handle the rest. After this, you can download mods and place them in your `.minecraft/mods` folder. For instructions on finding this folder on your system, please refer to [this article](https://minecraft.fandom.com/wiki/.minecraft#Locating_.minecraft). 

### Mods

Prospero runs the following mods client-side:

{:class="table"}
| Name         | What does it do?                                                                                              |
|--------------|---------------------------------------------------------------------------------------------------------------|
| ArmorPoser   | Allows modifying armor stand orientations, sizes and visibilities for various effects                         |
| Bobby        | Caches chunk data to massively increase render/visual distance                                                |
| Cloth Config | Allows other mods to have easily usable configuration screens                                                 |
| Fabric API   | The basis for all mods                                                                                        |
| Freecam      | Turns your vision into an external camera that can fly around freely like a drone                             |
| Iris         | Allows use of shader packs                                                                                    |
| Lithium      | General-purpose performance optimization mod                                                                  |
| Malilib      | Library mod used by MiniHUD                                                                                   |
| MiniHUD      | Configurable HUD that displays extra data on-screen, can also highlight specific in-game information visually |
| Sodium       | Graphical performance optimization mod                                                                        |
| VoiceChat    | Allows voice chat between connected players, and also supports custom audio files                             |

You can download these individually, or use Prospero's convenient [ZIP file](https://ellcrys.dyndns.org:14182/modpack/ProsperosMods.zip).

## Seed

The current world seed is `The Return of Chicken Jesus`, which is a reference to something that happened during an Ultra Hardcore session where we tried to defeat the Ender Dragon.

We do not currently have a world map, but you can [explore the biomes for this seed at ChunkBase](https://www.chunkbase.com/apps/seed-map#seed=The+Return+of+Chicken+Jesus&platform=java_1_21_9&dimension=overworld).