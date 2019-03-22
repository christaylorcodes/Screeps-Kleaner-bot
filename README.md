# Klean bot manofesto

>Klean bot was pushed to MMO server prematurly due to RoomPosition changes breaking my original code and not wanting to fix it. All of the listed items have not yet been coded.


### What is Klean bot?
---

Klean bot is a fork of [KasamiBot](https://github.com/kasami/kasamibot). Klean bot is meant to be an NPC of Shard 1.

The Kleaners are a people that want to save the Shard and help restore it to its natural beauty. They roam the edge of the Shard improving the screeps and the land they pass. They providing aid to needy screeps and perform restoration projects on near by rooms. They want to spread their aid and prevent over use of the land. Because of this they are nomadic and constantly on the move. Unlike most inhabitance of the Shard they dont want to stake out a claim and hunker down, they want to get out and see the Shard. 

They have adopted many standards to live by which they believe will bring peace and vitality to the Shard.

* 100% Wall free, walls are forever and litter our shard
* Free and open borders, dont block travel of screeps and leave ramparts public
* Conflict Free, there is enough energy & minerals for all of us
* Preservation, unclaimed rooms will be restored to their natural beauty
* Process power to offset energy footprint and invest in the future
* All minerals are mined in a sustainable fashion
* Screepitarian shipments of energy will be sent to nearby rooms in crisis
* Use links and terminals whenever possible to reduce unneeded transport intents
* All natural, organic, gluten free boosts
* Give back, 10% of profits will be returned to the local community
* Room controllers will be praised to the highest level ensuring as much energy as possible is returned to the shard. 
* Nuclear disarmament, nukes aren't good for anyone!
* Population control, less creeps will produce more ticks, for the whole shard.
* Reduce room usage, stay 10% bellow GCL with a cap of 30* rooms. Reducing a little can save a lot. 
* Work to reduce the effects of Shard holing

---

## Spec Sheet
* Klean bot will only occupy the edge sector
* Klean bot will only expand in a clockwise direction
* Once 30* rooms are established the farthest back room will be abandoned and the expansion clockwise will continue.
* every 2000 ticks 10% of storage values will be sent to nearby neighbors
* Base will be inverted for easy identification

![Base](https://i.imgur.com/perEGMR.png)

---

### Protesters


We believe that portals are caused by screeps and we need to act now to stop Shard holing. We will seek out these phenomenon and rally at them to bring attention to them now while there is still hope that we can change our ways.

![ProtestGif](https://i.imgur.com/r2txFfa.jpg)

---

### Kleansers

When population control measures take place at 30 rooms there will be a radical group that splits off the Kleaners.

* They will form a new expansion and become the kleansers.
* They will be aggressive to all neighbors as the only way to save the shard is rid it of those that pollute it.
* They will have a 1/5 chance of requesting minerals from kleaner base.
* There is a 1/2 chance that it will be the mineral they requested.
* The amount of minerals will be random.
* They will sell unwanted minerals on the market for a discount.
* Credits gained will be used to buy needed minerals from the market.
* If you are on the enemies list of the kleaners the kleansers will be even more agressive towards you
* kleansers will fly pirate flag and build upright
* players that attack this room will be added to the kleaners friends list
* This room will be abandoned and spawn at the front lines if it is the farthest back expansion or if there are no hostiles in range

---

### Why?

Screeps has been a great learning tool for me. I purchased this gaming having never written any javascript (PowerShell is my day job). I was able to jump through the tutorials read the API docs and I was off to the races. Already being familiar with reading API docs and basic programing knowledge I am sure my learning curve was not as sharp as some. As my bot and my knowledge gew I hobbled together code racing to keep up with my RCL. 

One tool that helped me and that I still love is the private server. I would load by bot in there and respawn over and over running super fast ticks and game mods I was able to get months worth of game time in days. This continuous build system help me work out issues and advance faster then I think I might have otherwise. After a while I had quite a few rooms and most economic items coded 'good enough'. By this time my javascript or rather typescript, skills had grown but my code was having some growing pains. I knew the best thing to do was a total rewrite but I was not sure my motivation could take that kind of a blow. so I stalled with military code, but I have always had reservations about being aggressive towards other players. 

So, defence code. But I needed some attackers....

So I started loading my private server up with public bots as opponents. But none of them where too aggressive so they where no help to my defence code. KasamiBot however did have some attack code and was in typescript so I thought I would just mess around with that to make it more aggressive. As I was poking around the fact that I needed to redo my code was more and more apparent. I saw things like classes that I knew nothing about and spurred another sense of learning for for better uses of the language. I started spending more time moding KasamiBot then my own bot.

My old bot has sat idle now on the public server for 6 months. During this time I have thought about the public bot on public server issue and NCPs. I chose to embracing the idea of a bot acting like an NPC. I feel most negative feelings about people using public bots is that they are not playing the game and essentially using 'cheat codes'. They are then using this advantage to run a muck in their sector. I have been actively coding on this base for quite some time and will continue to do so. This bot will be a friendly NPC and will give no unsolicited aggression to other players. It will in fact provide help to the players around it and offer them something to interact with.

And because who doesnt love script kitties!

![Kitt](https://i.chzbgr.com/full/8413491200/hBB191F41)

###### *lvl 8 rooms
