<span style="text-align: center; font-size: larger; font-weight: bold;">
    Quetzalcoatlus
</span>

## Features

* Web UI created to help in **managing** and **moderating** one (or more) [Path of Titans](https://pathoftitans.com/) servers.
* **Management**
    * 🔧 Toggle the availability of any dinosaurs, vanilla or modded[^1], with a simple button.
    * 👥 Manage whitelisted and banned players, plus administrators.
    * 🎮 Manage [player roles](https://hosting.pathoftitans.wiki/guide/player-roles) and their [permissions](https://hosting.pathoftitans.wiki/guide/chat-commands), quickly see role's members.
    * 🧩 Install mods with a single click.
    * 📄 Manage the server's configuration files (Game.ini, ...).
    * 📚 Browse created accounts and their characters.
* **Moderation**
    * 🎫 Treat reports as tickets, assign them to administrators, and keep track of their status.
    * 📝 Keep a historical record of all webhooks sent.
    * 🔍 Quickly see and filters all events involving a player.
    * ⚙️ Define custom rules to automatically run actions on players.
* **Miscellaneous**
    * 🗺️ [Leaflet](https://leafletjs.com/) map with each player's last-known[^2] position.
    * 📥 Possibility to download [server-side replays](https://hosting.pathoftitans.wiki/guide/replay-recordings#server-side-replays).

[^1]: Workflow still work-in-progress.
[^2]: From every webhooks having a "Location" field (`PlayerReport`, `PlayerLeave`, `PlayerKilled`, `PlayerRespawn`).