# mechjobmta
Its a simple mechanic job created using MTA:SA Lua .
First you need to be in a Civilian team to work like mechanic.
In server.lua file you can add your own validation where line is like : - if (getTeamName(getPlayerTeam( source )) == "Civilian")--[[ and classes[getElementData(source, "class")]] then
if you want to use class then create a table with values like :- classes = { ["Mechanic"] = true, ["Other value"] = true }

Hope you all enjoy it.

Thanks for downloading

For any bug report or suggestion please feel freee to contact at fear126@live.com
