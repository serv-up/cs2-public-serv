[<kbd><br>🌐 Русский README<br><br></kbd>](./README_RU.md)

# Public Server for CS2 by ServUp

Welcome to the official repository of the ready-to-use public server for Counter-Strike 2 (CS2) by the ServUp project. This server build is pre-configured and includes a wide range of plugins and enhancements to ensure optimal gameplay.

## Features

The server is equipped with the following plugins and tools:

- **Metamod**: [Metamod:Source](https://www.metamodsource.net/downloads.php/?branch=master) - A powerful plugin framework for games on the Source engine.
- **CounterStrikeSharp**: [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp) - A comprehensive API for CS2 plugin development.
- **ServerListPlayersFix**: [ServerListPlayersFix](https://github.com/Source2ZE/ServerListPlayersFix) - Fixes issues with player count display in the server list.
- **Chat Advertisement**: [cs2-advertisement](https://github.com/partiusfabaa/cs2-advertisement) - Displays custom advertisement messages in the game chat.
- **AFK Manager**: [AFKManager](https://github.com/NiGHT757/AFKManager) - Automatically manages AFK players.
- **Admin System**: [Iks_Admin](https://github.com/Iksix/Iks_Admin) - Provides a comprehensive admin management system.
- **Damage Info Display in Chat**: [CS2_DamageInfo](https://github.com/KitsuneLab-Development/CS2_DamageInfo) - Shows damage statistics in the game chat.
- **Player Ranking**: [Stats](https://github.com/partiusfabaa/cs2-ranks) - Tracks and manages player statistics.
- **Menu Manager**: [MenuManagerCS2](https://github.com/NickFox007/MenuManagerCS2) - Simplifies the creation and management of in-game menus.
- **Player Settings**: [PlayerSettingsCS2](https://github.com/NickFox007/PlayerSettingsCS2) - Saves and manages player settings.
- **Score Reset**: [SimpleResetScore](https://github.com/stefanx111/cs2-SimpleResetScore) - Easily resets the game score.
- **VIP Core with Modules**: [VIPCore](https://github.com/partiusfabaa/cs2-VIPCore) - A VIP system with customizable modules.
- **Weapon and Agent Skins**: [WeaponPaints](https://github.com/Nereziel/cs2-WeaponPaints) - Adds custom skins for weapons and agents.
- **Team-Based Weapon Restrictions**: [Weapon-restrict-fix](https://github.com/Nip0s/Weapon-restrict-fix) - Restricts weapon selection based on team.

## Requirements

To set up the server, you will need:

- **Hosting**: A game server hosting service.
- **MySQL Database**: For storing data related to plugins.
- **Web Hosting and Domain Name**: For setting up the web engine needed to select weapon and agent skins.


## Installation Guide

Follow these steps to install and configure your CS2 server:

1. **Download the server**:
   - [Download the pre-configured server build](https://github.com/serv-up/cs2-public-serv).
   
2. **Unpack the archive**:
   - Unzip the downloaded archive to the desired directory.

3. **Configure server files**:
   - Edit the following configuration files according to your needs:
     - `cfg/server.cfg` - The main server configuration file.
     - `addons/counterstrikesharp/configs/plugins/Advertisement/Advertisement.json` - Configures chat advertisement.
     - `addons/counterstrikesharp/configs/plugins/IksAdmin/IksAdmin.json` - Configures the admin system, including database settings.
     - `addons/counterstrikesharp/configs/plugins/IksAdmin_SocietyLogs/IksAdmin_SocietyLogs.json` - Configures Discord Webhook for logging.
     - `addons/counterstrikesharp/configs/plugins/RanksCore/ranks.json` - Configures the statistics system, including database settings.
     - `addons/counterstrikesharp/configs/plugins/VIPCore/vip_core.json` - Configures the VIP system, including database integration.
     - `addons/counterstrikesharp/configs/plugins/WeaponPaints/WeaponPaints.json` - Configures the skin selection for weapons and agents using a database.

4. **Start the server**:
   - Launch the server and enjoy a fully functional, feature-rich CS2 server.

---
For more detailed instructions and support, refer to the documentation for the individual plugins linked above, or connect with the ServUp community.

Feel free to fork this repository, submit bug reports, or contribute to the project!

## Conclusion

This repository provides a basic server configuration that you can extend with additional features based on your needs. However, if you want to create a high-quality and well-thought-out server build, feel free to contact us — we are happy to help everyone. Learn more on our website: [servup.net](https://servup.net).

To find the necessary plugin and keep track of its updates, join our Discord channel: [https://discord.gg/servup](https://discord.gg/servup).

## Looking for Opportunities

If you need an experienced developer for your projects, contact me:

- **Discord**: [https://discord.gg/servup](https://discord.gg/servup)
- **Telegram**: [https://t.me/serv_up](https://t.me/serv_up)
- **Steam**: [https://steamcommunity.com/id/nex-end/](https://steamcommunity.com/id/nex-end/)
