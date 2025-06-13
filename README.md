# ⚙️ Server util

This is the repository of my small plugin "server util". It adds a new command `/bserver` into the game, which acts like the `/server` command from Bungeecord and Velocity.

## 📂 Use cases
Some plugins support the execution of commands for players, like some NPC plugins.
The `/server` command provided by Bungeecord, Waterfall and Velocity is sometimes not supported, as it is a **proxy command** and local plugins on Spigot/Paper/etc. cannot access it.
This plugin fixes these problems, it adds a local command `/bserver` for use with other plugins to your server.

## 💻 Requirements
- The plugin was tested with **Minecraft version 1.20.x-1.21.x** but may also work with older versions.
- Java 17 (Version with Java 8 is in the works)

## 📤 How to install
1. Stop your server.
2. Put the plugin's JAR file into the `plugins` folder.
3. Start your server.

> [!WARNING]
> Using PlugmanX may also work, but is not recommended.

