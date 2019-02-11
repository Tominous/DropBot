
<p align="center"><img src="https://images.discordapp.net/avatars/487298106849886224/3a7aecf76365ae6df789ff9486a32d47.png"></p>
<h1 align="center">Apex Legends and Fortnite DropBot</h1>

<p align="center">
  <a href="https://discordbots.org/bot/487298106849886224" >
    <img src="https://discordbots.org/api/widget/487298106849886224.svg" alt="DropBot" />
  </a>
</p>

## Description
Automated Bot for Discord VoIP application and digital distribution platform. 

Randomly selects a location to start in for the Apex Legends and Fortnite Battle Royale games.

[Official Discord Bot](https://discordbots.org/bot/487298106849886224):
https://discordbots.org/bot/487298106849886224

A small, single-file, fully featured [Discordapp](https://discordapp.com) bot built using Node.js and [discord.io](https://github.com/izy521/discord.io).
Hosted on AWS.

## Add DropBot to server:

[Add to Discord](https://discordapp.com/oauth2/authorize?client_id=487298106849886224&scope=bot&permissions=0):
https://discordapp.com/oauth2/authorize?client_id=487298106849886224&scope=bot&permissions=0

### Usage instructions:
```
Add DropBot to a Discord server and see help by sending a "db!help" message in a channel with DropBot active.
   Will randomly choose a location in Apex Legends and Fortnite to drop.

Optional features:
db![option]    Description
-----------------------
db!                   : Uses the default command for choosing a drop location ("db!drop")
db!drop / db!fortnite : Randomly choose a Fortnite location to drop based on server settings.
db!apex               : Randomly choose an Apex Legends location to drop based on server settings.
db!mute               : Mutes DropBot audio in voice channel.
db!unmute             : Unmutes DropBot audio. Requires user to be in a voice channel.
db!settings           : Shows all DropBot settings on this server.
db!reset              : Resets all DropBot settings to their defaults on this server.
db!info               : Shows DropBot information and links/commands for additional help.
db!stop               : Stop playing audio and remove DropBot from voice channel.
db!help               : Show this help message again.
db!vote               : Check and update vote status for bot within the last 24 hours without rate limit penalty.
db!set  [id] [weight] : Change the percentage chance of choosing each Fortnite location. Use "db!set help" for more info.
db!aset [id] [weight] : Change the percentage chance of choosing each Apex Legends location. Use "db!set help" for more info.

-----------------------
db!set [id] [weight]
  Change the chance of choosing each location.

-------------- Fortnite ---------------
  ID   Location        Weight  % Chance
  -------------------------------------
   0 - Dusty Divot     - 5     - 4.8%
   1 - Fatal Fields    - 5     - 4.8%
   2 - Frosty Flights  - 5     - 4.8%
   3 - Tomato Temple   - 5     - 4.8%
   4 - Happy Hamlet    - 5     - 4.8%
   5 - Haunted Hills   - 5     - 4.8%
   6 - Junk Junction   - 5     - 4.8%
   7 - Lazy Links      - 5     - 4.8%
   8 - Lonely Lodge    - 5     - 4.8%
   9 - Loot Lake       - 5     - 4.8%
  10 - Lucky Landing   - 5     - 4.8%
  11 - Paradise Palms  - 5     - 4.8%
  12 - Pleasant Park   - 5     - 4.8%
  13 - Polar Peak      - 5     - 4.8%
  14 - Retail Row      - 5     - 4.8%
  15 - Salty Springs   - 5     - 4.8%
  16 - Shifty Shafts   - 5     - 4.8%
  17 - Snobby Shores   - 5     - 4.8%
  18 - The Block       - 5     - 4.8%
  19 - Tilted Towers   - 5     - 4.8%
  20 - Wailing Woods   - 5     - 4.8%
  ------------------------------------
Total weight: 105

------------ Apex Legends -------------
  ID   Location        Weight  % Chance
  -------------------------------------
   0 - Airbase         - 5     - 5.9%
   1 - Artillery       - 5     - 5.9%
   2 - Bridges         - 5     - 5.9%
   3 - Bunker          - 5     - 5.9%
   4 - Cascades        - 5     - 5.9%
   5 - Hydro Dam       - 5     - 5.9%
   6 - Market          - 5     - 5.9%
   7 - Relay           - 5     - 5.9%
   8 - Repulsor        - 5     - 5.9%
   9 - Runoff          - 5     - 5.9%
  10 - Skull Town      - 5     - 5.9%
  11 - Slum Lakes      - 5     - 5.9%
  12 - Swamps          - 5     - 5.9%
  13 - The Pit         - 5     - 5.9%
  14 - Thunderdome     - 5     - 5.9%
  15 - Water Treatment - 5     - 5.9%
  16 - Wetlands        - 5     - 5.9%
  ------------------------------------
Total weight: 85

[weight] can be 0 to 10.
 10 being most likely to be chosen.
  0 being a location that will not be chosen.

All locations default to a weight of 5.
Example: To remove Happy Hamlet from the list, send message:
  "db!set 4 0
Example: To set Snobby Shores to the max chance, send message:
  "db!set 17 10
  ```

### Requirements:
* **Node.js 0.12.x** or greater
* **ffmpeg/avconv** (needs to be added to PATH)
