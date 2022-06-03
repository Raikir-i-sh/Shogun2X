# Shogun2X
List of Total war Shogun 2 Mods I used to make gameplay 2x better

Tools : 
Pack file manager (PFM): To edit or create mods for Total war games that use .pack extension
EditSF : To edit save files . 
ModManager: To manage the load order of mods .

Edited_mods folder contains mods that I have heavily edited for which changes are written below. 
Unedited_mods folder contains mods that I haven't changed at all after downloading from steamworkshop. 

Note: First Download Darthmods Full Version and Launcher from moddb as it contains some amazing visual mods . Those mods are large sized so i can't upload it here.
The only file i've changed in darthmod is "darthmod_shogun.pack". So, other settings are your personal wish. 

About Darthmod : It's an amazing top-tier mod that enhances AI and CAI (campaign map's AI) and buffs up many other features of the game like unit stats, morale , Units size ,etc to make Gameplay last long (way too long) and have large-scale battles from the start. It also removes AI cheating to give you false sense of difficulty at Higher difficulty settings (which I hate) . It add many new changes to unit visuals and unit cards which looks way better than original.

Firstly, I didn't make Darthmod. I downloaded it (like u all) and played with it for few hours. I loved how AI becomes more clever in battle map and 
tries to flank in every chance it gets. CAI is also better as it focuses on economy and attacks with sufficient strong troops rather than annoying you
with low-tier units. What I hated about DM is morale changes. It buffs'em up too much so that every fight becomes "fight to death" which is not very fun imo.
The merit of flanking and hitting at rear becomes negligible due to high morale of even low-tier units. 

The changes are :
1. Unit size: 
Unit size is increased by 1.5x (optional) But after looking inside the mod file , it didn't actually increase no. of men for all, just for low-tier units and
some other units . I play TW at "Small" Unit size setting (coz my PC can't handle large) and with this, Yari Ashigaru had 90 men which i felt too much
for "small" and hero units were kinda unchanged. So....Number of men in every unit (except artilleries) have been buffed by 5-10 men in "small" setting.
This means in "ultra" setting , 5/0.25= 20 men to 40 men have increased depending on  unit-tier. 

DM doesn't increase 20 units per general to 40 . It just increases no. of men per unit. 
If you want to increase it, use EditSF to open any save file ,goto COMPRESSED_DATA -> CAMPAIGN_ENV -> CAMPAIGN_MODEL . At 9th row, You'll see 20. 
Change it to how much units per general you want. I used 24 insted coz 40 is way to cramped and auto-resolve for siege-attacker is too biased. 

2. Create cost and upkeeps :
Cost of units are basically same (only small tweaks) and upkeeps have been decreased little bit for low to mid-tier units.
Hero units and high-tier boats' upkeep has been decreased more to make'em more usable, economical. Heroes are not supposed to be "money-suckers" imo. 
Costs for normal clans & Specialty clans ( like Takeda for horses,etc) are nearly similar now. What makes those specialty units better is their 
Stats , not their low costs.

3. Garrisons :
This was optional in DM but a necessary one. But, DM make garrisons too OP. It provided high-tier units at Castle level 3 and above. Where did they come from?
So, now Garrisons are more balanced as it provides low-tier units only and other garrision units depends on the building you make in the province. 
For ex. making yari dojo gives you "yari samurai dojo" garrison ,etc. For this, "mod_dynamic_garrison.pack" is a must file that you'll find above.
Now, No-one(You & AI) can take bunch of low-tier units and capture 2-3 provinces in one turn by auto-resolving and moving on now.
This works well for sengoku right now. This does work for Rots & Fots but hasn't been balanced well. 

4. Morale : 
The entire morale changes by DM has been removed .Now, it is slightly buffed compared to original base game. So, Flanks, rear attack work as expected and
You don't have to "fight till death" to win every match. Note : High-tier units have high morale so getting them to route will take more time/kills .

5. Building : 
Building that provide any income give more money now. But , not in a game-changing way. For most of them, it's 50 - 100 more coins. This means the gap between
Barren soil and Very fertile soil has increased making them valuable. 

6. Food :
Making Trading port gives 1 food . Making market doesn't cost any food. 

7. Diplomacy:
I've checked this multiple times and found that some stats work , some don't . Trade starts 13 and ends at 90, increasing 3 per turn. 
Alliance gives you +150 decreasing to +70 by 2 per turn. Realm divide is capped to -60 (this might have changed in future) so that vassals and very close 
friends don't betray you. Note : These changes are save-game friendly. But at start of game , you'll still see Trade agreement at +15. Only when you 
make new Trade agreement, you'll see it start from +13. This system is still somewhat janky tho.

8. Unit Battle stats :
 DM had increased morale and made Archers basically useless by adding more 'spread' to projectiles. Now ,its not the case.
Archers work better than base game (not OP tho). Hero Archers might seem OP but they're heroes so that is expected.
Every archer's accuracy and reload skill has been buffed up by little But not Overpowered. 
And due to darthmod's AI changes, AI won't create large no. of archers. So, you'll see them in a balanced number.

Yari Ashigarus are no longer OP. But now, there are new high-tier Spear units (AUM-SHO mod needed) . So, stacking full of Yari-Ashigaru will get you
nowhere. Sword units are more strong and can kill Spear units with Yari-walls too. Nodachi's are more viable with their charge bonus buffed more. 
AUM_SHO is needed to get many new units. They have been balanced to match Darthmods' units. 

9. Tech-tree:
Half-Tech Mod needed. This DOES NOT make times in tech-tree halved But actually decreases time by 30% But some boring-type civil arts like (more tax ,
 +1 honor damnyo,etc ) have been halved so that those turns don't feel wasted. 

10. Horse Artillery mod: As it says, it gives u horse artillery that are bit faster with bit more ammo. 

11. Ambushes : 
DM launcher comes with 'freelancer's ambush mod' that changes battle-map to make Deployment area really close. Now , it actually feels like a ambush. 
Also, the control zone radius of general (the red circle you see around general in campaign map) is increased by 0.5 . Now, you don't have to be exactly at
edge of forest & hope that ambush works. Makes it bit easy to setup ambush now.

12. Navy : 
The control radius of ships have increased . Their upkeeps have decreased, Costs are same as base game. Navy Battles are still not fun tho. 
I simply auto-resolve them.

Finally , there are many other small tweaks done related to admin costs, Ninja's movepoints,Fatigue stats,Unit's movespeed, etc. But nothing too game changing.
there. Also, Yari-Wall formation can be used by most spear units now. 
The best thing about Darthmod is AI and No AI cheating (when AI create a full stack of units out of thin air just coz you're playing at "legendary"
difficulty) so I haven't changed anything for that.


