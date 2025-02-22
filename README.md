<p align="center">



## Setup

### <u>Before Installation:</u>

1. **Install Forge:** Ensure that you have [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.8.9.html) installed to enable mod compatibility.


### <u>Forge Installation:</u>

1. **Download:** Download the [VolcAddons-v2.9.14.jar](https://github.com/SchublLegend/VolcAddons/releases) file.

2. **Integration:** Drag into Minecraft mods folder (NOT the CT modules folder).

3. **El Fin v1:** You should be good to go! The mod will alert you if there is ever a new release in which you can just run `/updateva`!


## Commands

### <u>General Commands</u>

- **Settings**
  - `/va gui`: Allows user to move all active GUI locations.
  - `/va help`: Prints out the command help menu in game chat.
  - `/va settings`: Opens the settings' menu.
  - `/va toggles`: Opens the setting toggles' menu.
  - `/va version`: Checks if you are currently on latest version and prints out changelog.
- **Waypoints**
  - `/va cat`: Controls Montezuma Soul Piece location waypoints.
  - `/va enigma`: Controls Enigma Soul location waypoints.
  - `/va npc`: Creates waypoints to user inputted rift NPCs.
  - `/va zone`: Creates waypoints to user inputted rift locations.
  - `/va waypoint`: Creates waypoints to user inputted coordinates.
- **Lists**
  - `/va cd`: Tracks the cooldown of items using user inputted times.
  - `/va blacklist`: Block users from using leader/party commands.
  - `/va emotelist`: Set words to replace in user sent messages.
  - `/va warplist`: Set locations in which Diana burrow warp uses.
  - `/va whitelist`: Set player party invites to auto join.
- **Economy**
  - `/va attribute`: Various calculations that deal with attribute values.
  - `/va calc`: Various calculations that deal with general economical values.
  - `/va nw`: Calculates the networth of a SkyBlock profile using custom API.
- **Misc**
  - `/va splits`: Prints out Kuudra splits' stats.
  - `/sk`: Opens the SkyCrypt profile of inputted user.

### <u>Feature Commands</u>

- **Stats**
  - `/va stats`: Prints out SkyBlock tab stats.
  - `/va pet`: Prints out current pet.
  - `/va pt`: Prints out daily playtime.
  - `/va sf`: Prints out current soulflow _(requires accessory in inventory)_.
- **Status**
  - `/va fps`: Prints out client's FPS.
  - `/va tps`: Prints out server's TPS.
  - `/va ping`: Prints out client's ping.
  - `/va pitch`: Prints out player's exact pitch.
  - `/va yaw`: Prints out player's exact yaw.
- **Leader** _(Used in party chat)_
  - `?<allinv, allinv>`: Toggles party all invite.
  - `?invite [ign]`: Invites a player to the party.
  - `?demote`: Demotes the sender.
  - `?promote`: Promotes the sender.
  - `?<f, m, t>[1-7]`: Runs the specified join instance command.
  - `?stream [num]`: Runs the stream command to open the party.
  - `?transfer`: Transfers the party to sender.
  - `?warp`: Warps party into lobby.
- **Party** _(Used in party chat)_ - `?8ball`: Calls upon the Magic 8 Ball. - `?<coin, flip, coinflip, cf>`: Flips a coin. - `?<coords, xyz>`: Sends coordinates of players in patcher format. - `?<dice, roll>`: Rolls a 6 sided dice. - `?<fps, ping, tps>`: Sends specified stat to party. - `?help`: Prints out all party commands to chat. - `?<limbo, lobby, l>`: Forces users to go into main lobby. - `?rps`: Jan, ken, pon. - `?<w, waifu, women>`: I am very quirky.
  </br>

## Features

### <u>General Features</u>

- **General**
  - Armor Display (`/moveArmor`)
  - Equipment Display
  - Remove Selfie Mode
  - Render Waypoint
  - Skill Tracker (`/moveSkills`, `/resetSkills`)
- **Inventory**
  - Searchbar (`/moveSearch`)
  - Slot Binding (`/resetBinds`, `/saveBinds`, `/loadBinds`)
- **Server**
  - Hide Far Entities
  - Hide Close Players
  - Hide All Particles
  - Server Alert
  - Server Status (`/moveStatus`)
  - SkyBlock Stats Display (`/moveStats`)
- **Timer**
  - Item Cooldown Alert (`/va cd`)
  - Reminder Text
  - Reminder Time
- **Yapping**
  - Autocorrect Commands
  - Custom Emotes (`/va emote`)
  - Discord Webhook
  - Image Viewer

### <u>Party Features</u>

- **General**
  - Anti Ghost Party
  - Auto Join Reparty
  - Auto Transfer
  - Guild Join Message
  - Party Join Message
  - Server Kick Announce
  - Whitelist Rejoin (`/va wl`)
- **Party Commands**
  - Leader Chat Commands (`/va bl`)
  - Party Chat Commands

### <u>Economy Features</u>

- **General**
  - Bits Alert
  - Coin Tracker (`/moveCoins`, `/resetCoins`)
- **Pricing**
  - Container Value (`/moveContainer`)
  - Item Price (`/moveValue`)

### <u>Combat Features</u>

- **Bestiary**
  - Bestiary GUI
  - Broodmother Detect (`/moveBrood`)
  - Kill Counter (`/moveKills`, `/resetKills`)
- **General**
  - Combo Display (`/moveCombo`)
  - Damage Tracker
  - Low Health Alert
  - Ragnarok Detection
- **Gyrokinetic Wand**
  - Cell Alignment Alert
  - Cell Alignment Timer (`/moveGyro`)
- **Slayer**
  - Boss Announce
  - Miniboss Announce
  - Boss Highlight
  - Miniboss Highlight
  - Slayer Spawn Warning

### <u>Mining Features</u>

- **Crystal Hollows**
  - Wishing Compass Locator
- **Jinx**
  - 2x Powder Alert
  - Powder Chest Detect (`/moveChest`)
  - Powder Chest Hider
  - Powder Tracker (`/movePowder`, `/resetPowder`)

### <u>Farming Features</u>

- **General**
  - Jacob Reward Highlight
  - Farming Discord Webhook
- **Garden**
  - Composter Display (`/moveCompost`)
  - Garden Warp Override
  - Garden Visitor Display (`/moveVisitors`)
  - Next Visitor Display (`/moveNext`)
- **Pests**
  - Infestation Alert
  - Pest Alert
  - Plot Highlight
  - Pesthunter Display (`/movePest`)
  - Spray Display (`moveSpray`)

### <u>Event Features</u>

- **Great Spook**
  - Math Teacher Solver
  - Primal Fear Alert
  - Primal Feat Highlight
- **Inquisitor**
  - Inquisitor Detect
  - Inquisitor Announce
  - Inquisitor Counter (`moveInq`, `/resetInq`)
- **Mythological Ritual**
  - Diana Waypoint
  - Diana Warp (`/va warplist`)
  - Burrow Detection

### <u>Crimson Isles</u>

- **Fishing**
  - Golden Fish Timer (`/moveGolden`)
  - Mythic Creature Announce
  - Mythic Creature Detect
  - Trophy Fish Counter (`/moveTrophy`, `/resetTrophy`)
- **Vanquisher**
  - Vanquisher Announce
  - Vanquisher Auto-Warp
  - Vanquisher Counter (`/moveCounter`, `/resetCounter`)
  - Vanquisher Detect (`/moveVanq`)

### <u>Dungeons</u>

- **Star Detect**
  - Star Mob Highlight

### <u>Kuudra</u>

- **General**
  - Crate Waypoints
  - Kuudra Alerts
  - Kuudra HP Display
  - Kuudra Spawn Announce
  - Kuudra Splits (`/moveSplits`, `/va splits`)
  - Supply Pile Highlight
- **Profit**
  - Kuudra Profit Display (`/moveKP`)
  - Kuudra Profit Tracker (`/moveKPT`, `/resetKPT`)

### <u>Rift</u>

- **General**
  - DDR Helper
  - Enigma Soul Waypoint
  - Montezuma Soul Waypoint
- **Vampire**
  - Announce Mania Phase
  - Effigy Waypoint
  - Enlarge Impel Message
  - Vampire Attack Display (`/moveVamp`)
  - Vampire Hitbox
