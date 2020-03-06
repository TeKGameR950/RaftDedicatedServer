# RaftDedicatedServer

RaftDedicatedServer is a small project founded by TeKGameR & RaftModding.
The goal of this project is to fully recreate the networking of Raft based on a client-server protocol.

This will allow the following things :
 - Way more players. Easily up to 250. (Raft may not support it, but the dedicated server will handle it without any problem)
 - Completely Server Authoritative, Inventory, Player position etc. (No cheats & hacks guaranteed)
 - No need to have a second raft copy.
 - No need for an expensive windows vps. This will PERFECTLY run on a 1$ Linux VPS.
 - Way more possibilities for serverside plugins (Setting the player position, modifying inventory etc...)
 
However it also have some disadvantages :
 - Users that don't have RaftModLoader won't be able to join.
 - Will take a long time to code. Redoing an entire game networking isn't that easy.
 - Need a lot of software engineering to have both network solutions in the game. So you can still connect to your friends using the normal way.
 - Might take another long time to have a perfect sync of animations etc.
