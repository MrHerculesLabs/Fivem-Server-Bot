## Any Issues Open/Create a ticket within my discord!!
https://discord.gg/HerculesLabs

#### Installation
1. Download HeadTags 
2. Extract the .zip and place the folder in your /resources/ of your Fivem server
3. Start the resource in your server.cfg file
4. Enjoy :)

#### Works With BadgerPerms
[DiscordAcePerms](https://github.com/JaredScar/DiscordAcePerms)

[DiscordAPI](https://github.com/JaredScar/Badger_Discord_API)


#### How to set up it up
The 1s in this part of the server.lua file must be replaced with the IDs of your discord roles that are equal to the prefix you have associated with it:
```lua
roleList = {
{ROLE-ID, "~w~Civilian"}, -- Regular Civilian / Non-Staff
{ROLE-ID, "~r~T-Mod ~w~"}, --[[ T-Mod ]]-- 
{ROLE-ID, "~r~Moderator ~w~"}, --[[ Moderator ]]--
{ROLE-ID, "~r~Admin ~w~"}, --[[ Admin ]]--
{ROLE-ID, "~p~Management ~w~"}, --[[ Management ]]--
{ROLE-ID, "~o~Owner ~w~"}, --[[ Owner ]]--
}
