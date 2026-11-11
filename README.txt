MINECRAFT MODS WITH AI
By DaSbro Tutorial
https://www.youtube.com/@DaSbroTutorial

Two Minecraft Java Edition mods created with AI for the DaSbro Tutorial video.
You can install either mod individually or use both together.

REQUIREMENTS

Use this setup to match the video:
- Minecraft Java Edition 26.2
- Fabric Loader 0.20.1
- Fabric API 0.161.0+26.2
- Java 25

These files are for Minecraft Java Edition with Fabric.
They are not Bedrock add-ons or Forge/NeoForge mods.

INSTALLATION WITH THE MODRINTH APP

1. Create a Minecraft 26.2 instance using Fabric.
2. Make sure its Fabric Loader version is 0.20.1 or later.
3. Open the instance, select Browse content, and install Fabric API for Minecraft 26.2.
4. Return to the instance and use Upload content to add:
   - swap-bow-1.0.0.jar
   - villager-reactions-1.0.0.jar
5. Launch the instance.

Alternatively, place the JAR files directly in your Fabric installation's mods folder.
Install the regular .jar files, not source-code ZIPs or -sources.jar files.

For multiplayer, install the mods and Fabric API on both the server and every participating player's client.

MOD 1: SWAP BOW

Shoot a living mob or another player to instantly exchange positions with them.

- Uses normal arrows and bow charging.
- Swap arrows do not damage their targets.
- Successful swaps produce teleport particles and sounds.
- Successful swaps apply a three-second cooldown at normal game speed.
- Unsafe or invalid swaps are cancelled.
- Ordinary bows keep their normal behavior.

CRAFTING RECIPE

Use a crafting table:

Empty | Stick       | String
Stick | Ender Pearl | String
Empty | Stick       | String

Result: 1 Swap Bow.
The Ender Pearl is a crafting ingredient. Firing does not consume additional pearls.
You can also find the Swap Bow in the Creative Combat tab.

With commands enabled:
/give @s swap_bow:swap_bow

The destination checks prevent entities from appearing inside solid blocks.
They do not guarantee protection from falls, lava, or other environmental hazards.

MOD 2: VILLAGER REACTIONS

When a player kills a villager, nearby adult villagers gather around the player and deliver dramatic reactions.

- Detects adult villagers within 24 blocks of the killed villager.
- Villagers approach using normal pathfinding.
- Lines appear in chat with the speaker identified.
- Dialogue plays one line at a time.
- Lines do not repeat within the same scene.
- Further kills during an active scene do not start overlapping sequences.
- Villagers resume their normal behavior afterward.

Four voice recordings are included in the mod. The mortgage line is chat-only.
No separate audio download or resource pack is required.
Keep Minecraft's Voice/Speech volume enabled to hear the recordings.

Blocked paths or difficult terrain may prevent villagers from reaching the player.

TROUBLESHOOTING

"Requires Fabric Loader 0.20.1 or later":
Update the instance's Fabric Loader version.

Missing Fabric API:
Install Fabric API for Minecraft 26.2 in the same instance.

No villager voices:
Check Minecraft's Voice/Speech volume and the mod's audio configuration.

Both projects compiled successfully and passed their project checks.
Basic gameplay is demonstrated in the video. Compatibility with every other mod and every multiplayer setup has not been verified.

PROMPTS

See Prompts.txt for reusable prompts for both projects.
Custom voice recordings must be provided separately when recreating Villager Reactions.
Without recordings, the prompt asks for a working chat-only version.

USEFUL LINKS

Fabric: https://fabricmc.net/
Fabric API: https://modrinth.com/mod/fabric-api
Modrinth App: https://modrinth.com/app
DaSbro Tutorial: https://www.youtube.com/@DaSbroTutorial
