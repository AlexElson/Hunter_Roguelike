# Hunter_Roguelike
HunterRL is a survival wildlife-hunting 'roguelike' utilizing artificial intelligence to simulate animal behavior. Procedurally-generated landscapes are handled by the 'Diamond-Square' Algorithm, a method for generating heightmaps from a  grid of points. For each step of the algorithm, midpoints between all squares are deteremined by an average of those adjacent points - with an added random factor. Dijskstra's algorithm directs animals' pathfinding. Animals act intelligently based on their 'category.' Rabbits are attracted to the smell of carrots and can be lured into traps. Wolves, on the other hand, will chase down and attack the player, acting as scavengers attracted by the smell of any rabbit corpse.

This game was created during under a time-limit 2012 7-Day Roguelike Challenge.

![Alt text](/Screenshots/HunterRL_3.png?raw=true "Cover")

Your goal of is to hunt animals. 
Specifically: Rabbits and Wolves.

Use the Numpad to move around.
Pressing 5 will pass a turn.
Pressing p will allow you to pick things up.
Pressing o will allow you to open and close doors.
Pressing d will allow you to drop items.
Pressing i will allow you to see your inventory.
Pressing a will allow you to attack with what is equipped.
Pressing e will allow you to equip things.
Pressing E will unequip the item you have equipped.
Pressing t will allow you to throw items.
Pressing s while having a rifle equipped will allow you to shoot it.
Pressing 0 (Zero) while preforming an action will cancel it.

Rabbits are attracted by carrots.
Wolves are attracted by rabbit corpses.

While the Tracker is equipped, you will be able to see enemies who are out of your line-of-sight.
Rifles can be found on deceased hunters in the wilderness.

![Alt text](/Screenshots/HunterRL_2.png?raw=true "Cover")
