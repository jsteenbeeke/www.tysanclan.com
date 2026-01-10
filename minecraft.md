---
layout: page
title: Minecraft Server
permalink: /minecraft
---

<div class="hero hero-small">
    <h1>⛏️ Tysan Minecraft Server</h1>
    <p>Join us in our blocky adventures on our modded survival server</p>
</div>

<div style="background: linear-gradient(135deg, rgba(90, 103, 216, 0.1), rgba(72, 187, 120, 0.1)); padding: 2rem; border-radius: 1rem; margin-bottom: 2rem; text-align: center;">
    <h3 style="margin-top: 0; color: var(--color-accent-primary);">Server Address</h3>
    <code style="font-size: 1.25rem; padding: 0.5rem 1rem; background: white; border-radius: 0.5rem; display: inline-block;">ellcrys.dyndns.org</code>
    <p style="margin-top: 1rem; margin-bottom: 0; color: var(--color-neutral-text-light);">Running Minecraft Java Edition <strong>1.21.11</strong> with Fabric</p>
</div>

Prospero runs a _mostly Vanilla_ Minecraft Java Edition server. It is a Fabric server with a bunch of mods, a few datapacks, and a custom resourcepack.

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