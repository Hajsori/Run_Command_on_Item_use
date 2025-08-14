[![Join us on Discord](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/social/discord-plural_vector.svg)](https://discord.gg/ffbZyusxzK) [![Available on CurseForge](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/available/curseforge_vector.svg)](https://www.curseforge.com/minecraft-bedrock/scripts/run-command-on-item-use)

With RCoTu (Run Command on Item use) you can run **ANY** Command if a Player use (right click/hold down/...) a specific Item. It works also with Items from other Addons.

Example: If a Player uses a Compass then the Player is teleported to the Spawn.
 

How it works:

For example if you want to teleport someone who used a compass, you just need to do one of this Commands:

- `tp @a[tag="itemUse:minecraft:compass"] 0 0 0`
- `tp @a[tag="itemUse:minecraft:compass", tag="itemUseName:Spawn"] 0 0 0`
- `tp @a[tag="itemUseOn:minecraft:compass"] 0 0 0`
- `tp @a[tag="itemUseOn:minecraft:compass", tag="itemUseName:Spawn"] 0 0 0`

![A Command](https://api.mcpedl.com/storage/submissions/144125/images/run-command-on-item-use_2.png)
![Another Command](https://api.mcpedl.com/storage/submissions/144125/images/run-command-on-item-use_3.png)

