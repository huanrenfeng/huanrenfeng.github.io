---
layout: page
title: BaD
permalink: /BaD/
---

# Being a Doggy Change Log



## 0.86

1. I’ve successfully merged [Animated Animal Ears](https://www.nexusmods.com/skyrim/mods/35767?tab=files&BH=1 ) into BaD!

   And this version comes with a brand new MuST default preset for BaD, and the new default preset only uses these new ears from Animated Animal Ears.

   (I renamed the original preset “Disgusting Doggy Ears” preset, because they look filthy, haha 😂)

2. The doggy hood mentioned is included too. (As a resource, you can do what you want with it. The mod itself doesn’t use it.)

3. Implemented “no-dialog-interaction”. NPCs can sneaky to the doggy and fuck the doggy directly, with an MCM option.

4. Change “disable advanced doggy behavior” to “enable advanced doggy behavior”, making the “disabled” state as the default state. (Remind: advanced doggy behavior is to following a random NPC on its own mind)

## 0.85

1. New MCM setting:

	* Check Arousal For Talk Respond
	* NPC talk dirty OnlyWhen Arousal HigherThan
	* NPC talk coldly OnlyWhen Arousal SlowerThan
	* Germ Infection Settings:
	* Enable Magic Infection
	* Only Hostile Magic Works
	* Enable Weapon Infection
	* Enable Explosion Infection
	* Enable Ingredient Infection
	* Enable Potion Infection
	* Enable Enchantment Infection

2. Add a new Spell called “Magelight of Doggy Pack” which is available through Debug Menu’s Get Stuff Button.

   

   This magelight will mark the target for your doggy pack, and they will attack the target at your command

3. Add new “Horny Doggy Dialogues” if you are being a doggy and talking to another doggy.

   There are 7 different responds and result currently 

   (Depend on your status, you are not going to get all the responses at the same time).

4. Implemented the infection percentage on the Doggy Sex Curse (Previously left not implemented)

5. Might have fixed the “Have the effect in the menu but not being a doggy” issue. Improve MCM.

   Adds some new supporters’ nickname in MCM as acknowledgment. (Tell me if you don’t want your name on it )

   Officially Requires SexLab Arousal. ( In old versions, you could load the game with BaD installed without SLA, but in the new version, you’ll get CTD if you don’t have SLA installed ).

6. In the old versions, there’s an INI file that enables papyrus logging, this time the new version didn’t come with it, which could improve performance.

## 0.84

1. Fix the “no crawling no matter what” bug. 

	Bug description:

		If you forget to run FNIS before loading and saving the game with BaD installed, you will not be able to crawl.

	Fix:

		Every time you bring up “Doggy Power”, the mod will automatically detect if the animation data is outdated, if so, 
		the mod will update the required information, ultimately fixes the bug.

2. A new Doggy Pack Command “Start Attack Crosshair Target!”, which will order your doggy pack to attack the target.

	(Note: Doggy Pack Command only valid when you are a doggy yourself, and own some other doggies.)

	(Note: Combat started by your doggies won’t make you in trouble, which would be perfect if you don’t want to risk your life)

	a “Pack Flee From Combat” command.

3. MCM changes:

	Make “Automatically Equip Doggy Power” optional through MCM.

	An “Adopt Instantly” option. If this option is on, every time a doggy appears, it becomes your pet instantly. This option saves you from talking to multiple doggies to try to adopt them.

	A “Make Pet Essential” option. This would make sure none of your pets would die (Only apply to new doggies).

4. In the new version, Doggy Power will also be added if you are being a master of a doggy (because Doggy Power has some master commands ).  And the power will only be removed when you are not a doggy and don’t own any pets.

5. Rearrange commands in the doggy power. Rearrange MCM.

## BaD 0.83 (8/8/2020)

1. 		The new scratching animation 7z file is a patch file which would replace the old scratching animation. I didn’t add new animation but adopted the replacing method because in this way there will be less overhead for FNIS.
1. 		In the new version there’s a kick-ass animation,so you’ll need to run FNIS again.
1. 		New doggy-stalking feature can be toggled off by the option “Disable Advanced Doggy Behavior” in MCM.
1. 		Doggies will either cry for help or start to stalk a random Actor( maybe you ).
1. 		If the doggy’s confidence is cowardly/cautious, they will cry for help, and stay at the original place
1. 		If the doggy is brave or foolhardy, they will admit the fact that they are a doggy and try to stalk a random Actor, maybe you, maybe other NPCs
1. 		If the confidence is average, the doggy act randomly
1. Starting from this version, the doggy will only cry for help for 3 times before they act normally. It means that after 3 crying, they will start to do whatever they are doing before starting being a doggy.

## BaD 0.82 (8/6/2020)

1. infection slider imrpovement, see screenshot. ( sex infection configuration not implemented yet). 

	For example, if you set “%” to 23, and “%%” 73, then your chance to get infected would be 23.73%, or 0.2373.

2. kick ass animation; a new dialogue.

3. rename most fragment script files.  Fix some dialogue bugs in previous versions.

## BaD 0.81 (8/1/2020)

1. The doggy power panel has been upgraded! And  You can toggle crawl animations for normal walk and sneak as you wish!  A good feature for friends who don’t want followers to sneak like you, because you can just crawl without sneaking now!

	The setting is not temporary, meaning that next time you become a doggy, you won’t configure it again. 

	And this custom posture setting is only valid for the player character.

2. This time when you become a doggy, you’ll automatically equip the doggy power, press Z to use the power and the panel will pop up, with many convinent functions.
3. The Pet Powers is moved into doggy powers panel as well. And there’s a new button “Toggle Quick Invoke”. You can use this button to make the pet power messagebox show up instead of the doggy power panel.
4. There’s no Master powers yet. I’ll think of some.
5. The new doodle is brought in the new version too~

## BaD 0.801 (7/15/2020)

Fix animation name

## BaD 0.80 (7/01/2020)

Play along with MuST 0.25 is highly recommended. Open the MuST menu, find the file for Being a doggy, tweak armors as you wish. 

## BaD 0.79 (6/24/2020)

1. Talk to a doggy and say “Walk with me, we need to talk”. And you think of a way to persuade it to join your pack. 

2. And new Doggy Powers to summon, dismiss your pack. New power to start orgy within your pack. (They are all in the “Doggy Power” spell, you can get this spell by being a doggy. )

		Note: your pack is just the collection of all your pet doggies. By introducing a doggy pack,
		you can use various pack powers to manage your pets more easily. And because you can only command 
		your pack when you are being a doggy, this feature encourage you to be a doggy yourself.

3. fix several bugs about pets.

## BaD 0.78 (6/22/2020)

1. Native Doggy Ear Support! Introducing a pair of doggy ear, and the default MuST preset file for BaD is updated and contained in the new version!

		Try to install the newest MuST version 0.24 (See relevant Patreon post), and  then install this BaD version. 
		(If you do it in the backward order, the old preset file in MuST will cover the new preset, which is bad.) 
		After installation, try to be a doggy again. you’ll see the ears! (If you don’t like it, feel free to config it in MuST memu.)

2. When you are being a doggy and point your crosshair at another doggy, it wouldn’t say “SeekHelp”, instead it changes to “Doggy Chat”.

3. Make Doggy Goodbye Dialogue differ according to your doggy status. After you as a doggy finished the dialogue with another doggy, that doggy will only bark, and never say “don’t leave me~”

4. Change “Please release me~” to “Please help me~”

5. Fix a bug that when “SexCurse” option is on, sometimes non-vaginal sex triggers the doggy curse as well.

## BaD 0.77 (6/17/2020)

When you are being a doggy yourself, you won’t say “Hey doggy, nice butt!”. Instead, you can say “Pal Words”: “Hey, buddy, how are you doing?”. Wonderful things may happen between you and other doggies.

Add an option to toggle the orgy effect in DoggyKing’s Anger off.

## BaD 0.76 (6/12/2020)

1. Add a doggy “Wander” feature. You can toggle this on in MCM.

2. Add an option “Player Always Join” for the orgy. If this option is on, you will always join the doggy orgy. However, because the 4-person sex position is too rare, the mod didn’t adopt that, which means there may be a single doggy try to masturbate, in contrast to the original “player not always join” methodology.

3. Add an option “Allow Old Doggy Join” for the orgy. If this option is off (default), only new doggies affected by DoggyKing’s Anger will join the orgy. If this option is on, the mod will try to add nearby old doggies to the orgy as well.

		(The two options above are added in “Orgy” header for “Doggy Feature” Section.

4. Add a “Dismiss” line for DoggyKing to let you delete the statue. This version makes some changes to the doggyKing, making the statue incompatible with the previous 0.75 version. If you played 0.75 and placed a statue, please delete that one using the “MarkForDelete” command in the console (“Disable” command only disable the object, making it a redundant object).

5. Scale the DoggyKing Statue to half of its size, making it more approachable.

6. Brand new DoggyKing’s voiced dialogue! Every line of DoggyKing now is voiced!

7. Fix a bug that when “Disable NPC Doggy” is on, the orgy still applies to non-doggy.

8. Fix a bug that sometimes the doggy magnet effect in DoggyKing’s Anger is too powerful that it kills NPC. The mod will detect this and resurrect dead NPC doggy.

9. Improve code and MCM

## BaD 0.75 (6/10/2020)

Introducing DoggyKing which can be added through a button in Debug; Add dialogues for him. Talking to him will grant you the DoggyKing’s Anger.

Talk to DoggyKing to change the behavior of DoggyKing’s Anger.

Add a new orgy mode: line up fuck. Once triggered, doggies will line up waiting for being fucked. Once you fucked all of them, the orgy ends.

Every time you fucked a doggy, if you are a female, you will say “Oh yeah!”.

After fucked all the doggies, they will thank you and give you a small gift.

## BaD 0.74 (6/08/2020)

Add Doggy Magnet Effect to DoggyKing’s Anger. 

The  DoggyKing’s Anger now will pull the new doggies toward you and let you join in a big orgy!

The fact that whether you join in the orgy or not is decided by the following definition.

After dividing 3 into the number of doggies, if the remainder == 1, you will join.

## BaD 0.73 (6/06/2020)

1. Add a Remove-Item and Quest button.

2. Remove the “Ask Wizard quest” when you become a doggy. After this version, the wizard quest can only be triggered by an NPC dialogue.

3. Add a Force Animation Reset Button.

4. Add a Spell “Doggy Magnet”, you can pull any doggy toward you. Available through GetStuff button.

5. Starting from 0.73, BaD’s esp will revert to unlocalized one. But MCM remains translated.

## BaD 0.721 (6/04/2020)

All strings translated. Including dialogues. Tell me if you see any problem.

Localized for English, German, French, Spanish, Russian, Japanese.

## BaD 0.720 (6/02/2020)

Localized MCM for English, German, French, Spanish, Russian, Japanese. Other parts like dialogues are not localized because there’s too much work to do. But I localized the esp file anyway. Meaning that if you are not using the languages shown above, you need to use xTranslator to generate the corresponding strings file.

## BaD 0.712 (5/26/2020)

Fix punch animations for NPC doggies.

Run FNIS again and Click “Clean”  in the debug section.

(May: sick at home)

## BaD 0.711 (5/03/2020)

might have fixed the “Dead NPC endless script” bug.

## BaD 0.71 (4/28/2020)

1. Hide many doggy system-level spells in the UI so you won’t worry about them.
1. Add an option to disable NPC doggies. This option only disable future NPC doggies. If you want to clear current doggies, use the “clean” button in MCM->Debug
1. Now the “Hide Seek Help Prompt” option works for NPC doggies too.
1. Add an option to let you replace all the tags that the doggy animations involve.
1. Add an “Calm All as Doggy” option. If this option is on, every time you get hit by an enemy, the enemy will calm down.

## BaD 0.7.0.1 (4/23/2020)

Fixed a bug about “attack type” for all NPCs.

Fixed a bug about the side quest made in 0.7

## BaD 0.70 (4/22/2020)

1. After installing this version, you need to run FNIS and click “Clean” in MCM->Debug section.
1. Added a Side Quest to let a court wizard in Whiterun help you get the doggy necklace. You will not receive this necklace at the start of the game unless you go through the quest or use the cheat in MCM. You’ll not get the doggy curse spell and the doggy ritual spell for free either, starting from version 0.7.
1. Added a dialogue with the court wizard to bring out the Tale of Doggy King.
1. Added some doggy animations. Now NPC doggies will crawl when they are in combat.
1. Added a menu option to let you choose your combat style, between “Fist” and “Scratch”.
1. Added a cure self and a cure other spell. Currently available through MCM->debug->getstuff.

## BaD 0.69 (4/19/2020)

Rearrange MCM; Add a “Doggy Feature” section and an “Interact Feature” section.

Add a Doggy Power, a voice power which shows a function list available when you are a doggy. 

Add wash face function to Doggy Power; need to install Huan’s Anims Pack newest version to see the effect. And if it’s your first time installing the Anim Pack, you need to run FNIS.

Add a “Doggy Contagious” Feature. A doggy can convert others into doggies by having sex with them.

Add an option to disable “NPC releasing”. If “NPC releasing” is disabled, only pharmacists could cure you. (This function won’t work for NPC doggy, because making an NPC go to the pharmacist is not so realistic. You can hardly follow the doggy NPC to the pharmacist because it crawls too slow… )

Add more lines when an NPC tries to fuck you. Now NPCs have 2 different lines to say randomly for each sex position (doggy, blowjob, spank)

Fix a bug that despite you toggled on the option “Disable Interact Feature” in MCM, after having sex with a doggy it will call for help again.

Some minor bug fix and improvement.

## BaD 0.68 (4/18/2020)

Added a line when the guard tries to catch you. Say “I’m a doggy” and then he will spare you. I failed to get it run in my non-clean game but I get the line in a clean game ( thanks to my virtual machine~). 

I don’t know what’s wrong. ( Clean game is not like clean save, I tried a clean save but still nothing… I think there must be something wrong with my mod list. The dialogue is added successfully in a “Clean Game” in which only necessary mods for BaD are installed  )

Added an option to let you disable the calling feature. After disabled any doggies will not call for help and you’ll not receive the “Interact with the doggy” quest.

Added an option to make the reacting NPC crawl as well. 

Fixed a bug that when you become a doggy, the mod still makes you sneak when the “classic trigger” is on.

Fixed a bug that if you talk to a doggy after its help cry, if you release it, it will still be treated like a doggy by the mod even if it is actually reverted to human.

Fix some subtle bug that is hard to explain. 

Renamed “Classic Fuck trigger” to “Classic trigger”

Renamed “Everyone can fuck doggy” to “Doggy can fuck doggy”. I was being vague, this option makes doggy be able to fuck another doggy.

## BaD 0.6.7.1 (4/17/2020)

Fixed a bug that the “go-to warm place” feature didn’t work.
Fixed a bug that the “go-to pharmacist” feature didn’t work.
Improve the voice files, make the files smaller. And makes the “Good Dog” line avaliable for every voice type.
Also a notice that after 0.6.6 you won’t need to download “Nymra’s voice files” in the loverslab anymore, because I included them in the main mod.

## BaD 0.6.7.0 (4/14/2020)

Implement the “Go to warmer Place” feature for all places.
Implement the “Go to the pharmacist” feature for all cities.
Fixed a bug that the “Pharmacist dialogue” shows for everyone.
Perhaps fixed the dodeed bug that if multiple NPC-Master-doggy pair dodeed function is running, the doggies might go to one master instead of their own master.
(All changes not tested, making this version not working)

## BaD 0.6.6 (4/8/2020)

Adjust the Petting Animation. Now you will be moved near to the doggy and pet it. When you pet it, it will not move but wait for you to finish.

Now you’ll say “Good dog” when you are petting it.

The voice file has been added for voice FemaleCommoner, FemaleEvenToned, femalekhajiit, female Nord, FemaleCondescending, and FemaleArgonian.

Add the “Go to Pharmacist” feature. When an NPC tries to release you, the local pharmacist might be pointed out. Currently, it only works for Whiterun.


## BaD 0.6.5 (4/3/2020)

Add a feature Pet Doggy which lets you pet any doggy you are talking to. Need to run FNIS again.

Add a feature “Sex Curse” which can be enabled in MCM. Whenever you had doggy position sex, you will become a doggy. 

Seek Help Feature Adjustment

Remove the option “SeekHelpRarely” and “Player Seek Help Interval” in MCM.

Add the option “Set SeekHelp Interval” and “Random SeekHelp Interval” in MCM.

The default cry interval has been adjusted to 6 seconds.

Now the “You are crying for help” prompt will only show once for the first time you cry. 

And you will stop crying after 3 times of trying

In the old versions, the cry implementation was not accurate. The cry interval for the player is about 3 seconds shorter than the interval for NPCs. This version fixed this issue.

Adjust some text in Notification. Adjust MCM.

Fix an old bug that the player won’t be affected by the seek help interval setting after the first cry.

## BaD 0.6.4 (4/2/2020)

Add an option “Disable Do Deed Feature” in MCM

Adjust some text in MCM and Notification.

Fixed a bug that if an NPC has a doggy, when you acquired a new doggy, the NPC’s doggy will start following you instead of following its master. This fix introduces a new NPC-Follow-NPC mechanism, allowing at most 23 NPC_Master-Pet pairs.

Fixed a but that “Do Deed feature” doesn’t work for the “NPC master and NPC doggy” pair.

## 0.6.3 ( 2020-3-29) (with SE version)

Replace doggyAutoFuck_huan with BeingADoggy_huan, including file name and file content.

Fix a bug that if travel back and forth, the seek help event won’t refresh.

You need to reinstall the mod.

Uninstall the mod after you hit the clean button in MCM, 

and install the new version,Run FNIS,  enter the game,

open MCM once but don’t enter the BeingADoggy menu,

quit MCM, wait until you see “MCM: Registered 1 New Menu(s)”

(3.2- 3.28 making “Your Sister”, “EggFactory Huan’s Addon" and “MuST”)

## 0.6.2.3  (2020-3-1)

Replace every bear trap into the doggy ones

(2.8 - 2.29 making “Your Sister” and “MuST”)

## 0.6.2.2 (2020-2-8) (with SE version)

Adds an option to add a “Clear Spell” in debug section, so that you can clean all the pets with a single key instead of opening the MCM.
Improved the codes to prevent some issue about the preset choosing UI.

## 0.6.2.1 (2020-2-6)

Add an “Everyone Can Fuck Doggy” option which allows doggy fuck doggy.

It only works when you are using “Cloak mode”.

## 0.6.2 (2020-2-5)

Improve the relationship between masters and resentful pets. New resentful pets will attack masters.

Add the option “Keep Level1 Aggression” to prevent NPCs from joining the fight between master and resentful pets.

Adds the NPC curse PC function !! Now every NPC attack might curse you. It can be turned off in MCM.

Contains the new animations, need to run FNIS again.

## 0.6.1

Rearrange the MCM menu.

Added an option “Ask MuST preset” in MCM. When toggled on, each time a doggy appeared, you can choose which species should it be. Cooperate with MuST 0.1.5 or higher version.

Introduce a soft dependency on UIExtension. Install UIExtension and   MuST 0.1.5 or higher version before update to this version to use the preset feature.

## 0.6.0.1  (2020-2-2 )

Fixed a bug that after the nemesis was cured, the quest mark still says it’s a resentful doggy.

Fixed a bug. Before the fix,  after a save reload, the quest mark of a doggy will be canceled. In this fix,

the mark will be shown again in 2 seconds.

## 0.6.0  (2020-1-31 )

1. Add an “Always Level Up” option in MCM. If it’s on, the nemesis will always level up after having beaten and fucked a target.
1. Add an “Lose Sperm” option in MCM. If it’s on, the nemesis will lose sperm each time it fucked a target. The amount of sperm starts with 100. If the sperm falls to zero, then the nemesis will be cured. And a messagebox will showup to notice you this.
1. Add an “Lose Sperm Amount” slider in MCM to let you slide the amount of sperm the nemesis would lose. 
1. Add an “Hide Seek Help Prompt” option in MCM.
1. Adjust the slider of the “Player Seek Help Interval” option. Now the SliderInterval is 5 and the range is from 0 to 600 ( 10 minutes ).
1. Fixed a bug in 0.5.9.3 that the Nemesis can not attack the player.
1. Fixed a bug that the Nemesis can not calm down properly.
1. Make sure you have clicked the “Clean” button in MCM debug section before and after the new version installation. Or just use a clean save.

## 0.5.9.3  (2020-1-29)

1. Fixed an old issue that when the PC travel, the NPC master of another pet might be hostile again to their own pet.
1. Fixed an old bug that the curse won’t calm down NPCs.
1. Added a new option in MCM to copy all of the master’s faction to the pet.
1. Need to click “Clean” button.

## 0.5.9.2 (2020-1-28 )

1. Fixed a small bug that the “Enable Sexlab Arousal” button in MCM takes no effect.
1. Fixed an issue that the cloak mode sometimes doesn’t work properly. This time the aggressor will be triggered sooner.
1. Make sure you have clicked the “Clean” button in MCM debug section before and after the new version installation.
(1.27 mourning Kobe, drawing his portrait. )

## 0.5.9.1

1. Fixed a bug that the “very aggressive” function didn’t work.
1. Adds an option in MCM’s debug section to adjust the CrawlFix wait interval, might be helpful for slow computers.The higher the interval, the more likely the doggy will be crawling again , the more waiting time for the crawling.

## 0.5.9 (2020-1-26 )

1. update seq file
1. Adds an option in MCM to make the resentful doggy starts with a “very aggressive” agression which makes it attack Enemies and Neutrals on sight.
1. Adds an option in MCM to make the resentful doggy follow the player (when it’s calm ). 
1. Implemented the doggy->NPC function of the Nemesis feature.
(1.23-1.25: vacation, making animations )

## 0.5.8.2 (2020-1-22 )

Fixed a bug that after being cursed by the door/corpse, you might still see the notification when the condition meets again.
Added an option in MCM to let you change the “spanking” animation’s tag.

## 0.5.8.1 (2020-1-21 )

1. Added a new feature to trace every new faction the doggy was forced to join by his master,   which allows the “Clean” button to restore their initial faction state.
2. Fixed a bug that feature “Dangerous door/corpse” doesn’t work.

## 0.5.8 (2020-1-19 )

1. Made a new sneak idle animation,  more realistic and sexier than the original “Crawl on Fours” one. 
1. Made a new sneak left hand attack animation( bare hand, sneak_h2hattacklefthand). Need to run FNIS again and click “Clean” button in Debug section in MCM
1. Added voice files to Male PC’s line “Let me fill your 
(1-17: making 3d object )

## 0.5.7 (2020-1-16 )

1. Renamed “SeekForHelp” to “SeekHelp”. 
1. Added a toggle “No Rape” in Nemesis Feauture section in MCM.
1. Added a toggle “Don’t run away” in Nemesis Feauture section in MCM.

		Note that due to the confidence of the resentful doggy or avenger is not high enough, 
		it will still run away sometimes.
		
		
		Note2: the Nemesis feature changes the Confidence and some more attributes, 
		which might cause trouble if your doggy is not unique like some guards, 
		bandits or random enemies.
		
1. Moved “Resentful Instantly” to Nemesis section

## 0.5.6 (2020-1-15 )

1. Changed the “Being a Doggy!” quest name to “Being a Doggy (pet)!”
1. Changed the doggy mark quest name to “All the pets (doggies)”, refering “doggy” as “pet”
1. Renamed the “Doggy Fuck Curse” to “Doggy Curse”.
1. Adds quest mark to abandoned pets, resentful pets, avengers and nemesises.
1. There could be infinite resentful doggies.
1. Fixed a small bug in MCM,introduced in 0.5.5 

## 0.5.5 ( 01-13 )

1. Fixed the NPC animation bug from 0.3.0 by adding a dozen of animations to the walking and running ones. Need to click “Clean” button in MCM or use a clean save. Need to run FNIS again. 
1. Implemented the resentful doggy level up function. After raping, a messagebox will show up implying the level up event.
1. Added a Nemesis section in MCM. Via this menu, you can check every abandoned pet, see its nemesis level and if it’s resentful.
1. “Doggy Nemesis” has been renamed to “Nemesis”. And I’ll refer to it as “resentful thing” sometimes because of its evilness.

## 0.5.4.01 ( 2020-01-09 )

1. Fixed a bug that when the doggy performs a kill move, the player will die instead of being fucked.
1. Fixed a bug that after being fucked by a resentful doggy, the player will be essential that nobody could kill you.
1. Change the way the resentful doggy goes away after fucking.
1. Catch an issue that when the resentful doggy goes away, it walks but doesn’t crawl. It is caused by a un-fixed bug from 0.3.0.
(01-08 making animation) 

## 0.5.4 ( 2020-01-07 )

1. Adds NPC->PC sex function to feature Nemesis.  Need to click “clean” button in MCM or use a clean save.  
1. Update the doddle.
1. Rename the “Doggy Fuck Curse” to “Doggy Curse”
1. Rename the ModName in MCM to “Being A Doggy”. Need to use a clean save to see the change of name in MCM.

(2020-01-03-06 learning textures, 3d modeling)

(2020-01-02 making animation)

(2020-01-01 rest)

(2019-12-31 studying SexLab Defeat)

(2019-12-30 making animation )

(2019-12-28 - 29 making MuST)

(2019-12-27 painting )

(2019-12-26making animation )

## 0.5.3 (2019-12-25)

1. Fixed a bug that sometimes we can’t cast the curse on the former-doggy.
1. Fixed a bug that when the player doggy (you) are going to have sex triggered by BaD mod, the mod will strip the cursed item, which leads to reverting to human.
1. Fixed a bug that in fact the female PC can speak with the male voice too, which is not supposed to happen.
1. Fine tune unstrip interval to 0.4s to adjust to MuST’s stripping progress.
1. Catch an issue that when you equip a enchanted doggy-curse item, and MuST is on , in whose JSON file there was written to be an Armor to wear that match the cursed item’s slot just by coinsidence, then you can not get rid of the curse easily. Once you hit clean button, the doggy suit will be removed and your original suit will be put on  again, which curses you again. To get rid of this issue, toggle off the “Do Strip” option, and clean some more times and you will finally get rid of this.
1. Add an option in MCM->Player-> No Player Voice, which toggles the PC’s voice.
1. Add an option in MCM->General-> Strip Weapon. Now you need this option on to strip weapons automaticaly when crawling. ( The mod still sheathe the weapons, weapons just hang in your belt or on your back, instead of going into your pocket.)

## 0.5.2 (2019-12-24)

1. Fixed a bug that when cloak mode is on, if you abandoned the doggy, it might be fucked by a second NPC when it’s getting fucked by the first NPC.
1. Fixed a bug that nothing, instead of a quest, happens after abandoning the doggy.
1. Catch a bug that if you recovered a doggy, sometimes you cannot cast the curse on it anymore. I will fix it later.
1. Add a new voice to the line “Fine, poor doggy”. Need to go to loverslab to download the voice file.
1. Adds a new feature to make the abandoned doggy a resentful doggy. Get a resentful doggy through MCM or making NPCs fuck the doggy 3 more times. A resentful doggy cannot be killed, and will attack masters who had abandoned a doggy ( includes you ). After beaten, it will go into bleedout mode, calm down for a short time and flee from you. If it beats you, it will have sex with you and flee from you (sex feature not implemented yet).
1. Adds the following options in MCM:
1. General -> Disable Doggy Nemesis   the doggy won’t be resentful at all no matter how long since you abandoned it.
2. NPC -> Resentful Instantly  the doggy will be resentful the instant you abandon it.

## 0.5.1 (2019-12-22)

Fixed a bug that when you are a doggy, some features won’t work properly.
Update seq file
Adds a voice voiced by Nymra to the line “Hey doggy, nice butt”. Need the PC to be male to hear it. If your character is female, just type “showracemenu” in console triggered by “`” and adjust your sex to male. Need to download the voice file from Loverslab. Because the files are voiced by Nymra.
Need to use a clean save or click “clean” button before and after reinstall the mod.

## 0.5.0.12  (2019-12-20)

Fixed a bug that if cloak mode is off and the doggy cannot find an NPC to deal with it by the first cry, it won’t cry for help for the second time.
Fixed a bug that if multiple doggies are presented, after the first doggy gets fucked, the second doggy won’t act properly.
Fixed some other bugs that occurred in 0.5.0.11

## 0.5.0.11  (2019-12-19)

Improved and rewrote codes
fixed a bug that if MuST is enabled, and when the doggy have sex, the armors equipped by MuST will be removed. Need to use MuST 0.08 or higher version to get rid of the bug.

## 0.5.0.10 (2019-12-18)

improve codes
Adds a slider in MCM->Debug to let you set the UnStrip Wait interval. This is prepared for cooperating with MuST. When MuST is enabled, there is a chance that it strips your clothes which were just put on by BAD. If you see this bug, adjust the interval until it’s gone.

## 0.5.0.09 (2019-12-16)

Fixed a bug that when MuST is on, and in the JSON file it is supposed to add and remove some armors, after reverting to human, the doggy will be naked instead of dressing their old armors.

## 0.5.0.08  

improve some codes.
Fixed a bug that if the MuST is enabled, the Armor management is messed up.

## 0.5.0.07

Fixed a bug that when you travel back and forth and talk to the doggy again to release it, the releasing doesn’t work.
Remove interaction quest mark when you fast travel. You can toggle on the overall doggies marker in the MCM->Debug section

## 0.5.0.06  (2019-12-15)

Fixed a bug that the mod didn’t dress the doggy properly after reverting to human, when you save the game and load the game again or fast travel. This time after fast travel the fix won’t put on clothes on doggy.
Fixed a bug that after the fix spell, the texture in MuST will be added twice and cannot be removed.
(13-15: make MuST)

## 0.5.0.05 (2019-12-12)

Add a new MCM option to let you toggle whether the master will go to his home instantly. If he go home instantly, you can use jump to bring up the option window and choose to teleport to your master. This new option might be useful when the NPC’s home is a outdoor place, or when you want to save some time.
Adds MuST framework integration. If you installed MuST 0.0.1, you will see that when a human becomes a doggy, it will equip some armor. More information in the MuST mod description.
Make the clean function close the Doggies marker.
Fixed a bug that after fast travel, if you casted the cursed on some NPC before, and he is not following you now, then if you click “Clean” button in MCM, the doggy will not be cleaned.
Fixed a bug that if you stripped the doggy before and fast traveled, the doggy’s clothes will be gone forever. the new fix will unstrip the doggy when you fast travel.

## 0.5.0.04 (2019-12-11)

Catch a bug that when you ask somebody to take you home, they just standstill. This is because the place where you are is exactly your master’s home.After the fix, when this happens, a notification will show up to tell you this.
Fixed a bug that when you leave your master, he will still look at you and go to his home.
I think the bug shown in the recent demo is not an “in scene” bug. I believe that he is not in any scene but just has a blocking dialogue. Perhaps anyone who has a blocking dialogue can not do their deed.

## 0.5.0.03 (2019-12-10)

Remove the “must not In scene” limit.
Add a limit that the NPC must be a human to have the potential to be a doggy.

 

## 0.5.0.02 (2019-12-09)

Adds a sub-function to the bark function. When your master is too far from you, he will come to you. When your master is too close to you, he will get away from you ( follow his old path which is before having adopted you ).
Remove unnecessary test meshes and textures which are just for the author’s practice.make the mod much smaller.

## 0.5.0.01 (2019-12-07)

    fixed a bug that after barking that makes your master follow you, if you leave your master, your master will still follow you.

## 0.5.0 (2019-12-06)

Adds a new Ritual Doggy Curse called “DoggyKing’s Anger” which makes all people around you become a doggy. This effect only lasts 15 minutes. The effect is temporary and will be dispelled by fast traveling too ( immunes to the fast travel bug fix ).A piece of music is played alongside the spell, try it! (You need to turn up the music volume in the settings menu). This spell is added by MCM->DEBUG->get stuff , and this spell would not trigger the NPC interaction scene, which is intended.
Adds a button at MCM->Debug->Toggle Doggies Marker, which shows 10 available doggies at the map.
Improved the fix for the fast travel bug. Now when you are near the doggy, it will be fixed automatically. If you still see bugs, you can go to MCM to get the fix spell and cast it to the doggy manually.The fix is not fully implemented and will be in the future.

## 0.4.9 (2019-12-05)

1. Make the “gift function” and abandon function work again.

2. Catch a bug in 0.4.6 about fast traveling. Working on the solution. Avoid fast travel to temporarily avoid the bug .

	I made another temporary solution too. You can go to MCM->Debug->add FixDoggySpell, this will give you a spell

	called Doggy Fix Spell. When you see your doggy loses crawl animation and doggy dialogues, you can cast the spell on your doggy.

	After that the doggy might act normal again. This fix, which cannot fix every problem , is not perfect and I’ll improve this in the future.

	More details about the fix and the fast travel bug in this version

		the bug is caused due to the fact that all doggies functions are based on a magic effect starting from 0.4.6, and 

		fast traveling will dispel every magic effect on every NPCs.

		the bug will: 
		
			make the doggy’s animation revert to normal instead of crawling.

			make the doggy forget its data.

			not stop the “NPC interact Quest”, but interupt the scene. It was going to stop the quest before I did some works to walkaround it.

			not remove the “package” on the doggy. (Package is a AI stuff making the NPC act whatever you want). So you’ll see

		the doggy is still following you if it’s yours or just stay at the original place if it has no master. 

	It was going to remove the package before I did some works to walkaround it.

	the fix spell can 

		fix the doggy if it is adopted by you.

		not completely fix the doggy if it is adopted by NPC.

		fix the doggy if it is not adopted by anyone.

	after the fix the doggy will forget how many times it got fucked or fooled. 

3. Also found that after 0.4.6 the enchantment does not need to be dropped, like the demo video shows , to work, which is good news.

4. New plan for Nemesis: there can be infinite doggies abandoned, but there will only be one Doggy Nemesis( one resentful doggy, one avenger doggy).

## 0.4.8 (2019-12-04)

make cloak mode and “Do Deed” function work again
Fine tune the descriptions of magics.
fixed some bugs
make the doggy quest named “Doggies” and be a side quest.

## 0.4.7  (2019-12-03)

Main features have been partly rewritten, make the multiple doggies work.
fine tune some lines.
the doggy will become human again after 10 days.
A new bug that after your fast travel , the doggy will revert to human again.
0.5.0 (plan written on 2019-11-30)

Rewrite the whole mod, make infinite doggies work.

## 0.4.6 (2019-11-29)

1. Adds a new feature : abandon doggy. You can abandon your doggy through dialogue. After that, the doggy will still be calling for help with a larger interval. And if the doggy was fooled 3 times more, the doggy will not call for help ever again. And it will become a resentful doggy that attack NPCs around occassionally.(Attack function haven’t been implemented yet). After having abandoned the doggy, you can’t adopt or interact this doggy any more. (This is not like release the doggy.)
1. Adds a MCM option to let you slide the abandoned doggy’s seek for help interval
1. Adds a animation file so when you are a doggy and draw the weapon, you won’t stand up but will remain crawling. Need to run FNIS again and click “Clean” button in “Debug” section in MCM.
1. Adds some emotions to doggy’s hello line.
1. Fixed a bug that when a doggy is following you, you can still ask it to follow you.
1. Fixed a bug that if a doggy is following you and the cloak mode is on, other NPCs will still react to the doggy ( Because the cloak was not cancelled ).
1. Fixed a bug that if an actor is reacting the doggy and you choose to adopt the doggy, the actor will still fuck the doggy.

## 0.4.5 (2019-11-27)

1. Adds a feature that when you bark, your master will follow you.
1. Makes the actor sheathe the weapon the moment it becomes a doggy and remove them after 2 seconds.
1. Adds a MCM option to toggle the Immersive Comment.
1. Adds Info Text to many MCM options.
1. Fixed a bug that if you leave your master, your freewalk state won’t change, and will be reflected when you are following your next master.
1. Fine tune some line’s emotions
1. Make the “By the gods” line not be said in 30 minutes (in game).

(26: had a fever)

(22-25 : making animations)

## 0.4.4 (2019-11-22)

1. Adds 3 functions aviliable via jump  when you are a doggy who has a master “toggle free walk” , “teleport to master”, “bark" 
1. Fixed a bug that if you are in “Cloak mode”, and you are not a doggy later, the cloak spell won’t disappear.

## 0.4.3 (2019-11-19)

1. Adds a dialogue to let the master bring you to the master’s home. Currently only works for PC.
1. Make the “Cloak mode” work for NPC doggy. Need to go to MCM’s Debug section and click “clean” first.
1. Fixed a bug that non-master NPC will have the “bond” line too.
1. Fixed a bug that in “Cloak mode” a doggy can react to another doggy.
1. Fixed a bug that you will be locked outside the master’s house
1. Make the master not say the “immersive comment”
1. Remove some “naked comment” possible for some voicetypes because they will still say this if the doggy are not naked.

## 0.4.2 (2019-11-17 feel better.)

1. Add spanking and blowjob to NPC-NPC dodeed function.
1. Add an option “Cloak instead”. With this function you will not calling for help, any NPC near which fits the conditions will interact with you instantly. Currently only works for PC.
1. Fixed a bug that the interacting NPC won’t look at you when they are saying “By the gods.”

## 0.4.1 (2019-11-12 got flu)

1. Made some sneak animations, now when running the sneak animations you will  neighter spin nor sneak like valina ones (stand up instead of crawl).
1. Adds a feature that the doggy will whine when PC finished talking to it and may bark after leaving dialogue.
1. Improve the Hello line of PC’s doggy.
1. Fixed a bug that when the doggy says the Goodbye line it will stand up shortly by replacing the goodbye lineand animation things.
1. Fixed a bug that you can give the doggy to the doggy itself.
1. Fixed a bug that after you adopt a doggy, if the doggy was going to “calling” , it will still call one more time.

## 0.4.0 (2019-11-9)

1. Adds an option in mcm to toggle “Need LOS”.
1. Adds an option in mcm to toggle “NPC SeekForHelp Silently”.
1. Adds blowjob and spanking to NPC->NPC and PC->NPC doggy fuck scene.
1. Improve code, improve animation transition when the NPC doggy will go into sexlab fuck scene.
1. Fixed a bug that creatures also have “immersive hello line”
1. Fixed a bug that if the PC follows the master, the PC will still “calling for help”
1. Fixed a bug that when the PC “SeekForHelp” from a dialogue, the NPC might ignore the PC by saying “What are you doing that for”

## 0.3.9 (2019-11-7)

1. Adds “Do Deed function” to “NPC follow NPC feature”.
1. Adds headtrack to scenes that I forgot to add.
1. Adds the “Gift function”. Now you can give your doggy to others. Don’t forget that once the master get a doggy,   the master will do his deed when the time comes
1. Update the Seq file so that the mod will work properly in a clean save without any issue.
1. Adds a blowjob feature. When an NPC decides to fuck you , he might make you give him a blowjob.
1. Adds a spanking feature to PC fuck scene. Tested with Cobalt Animation Spanking Pack.
1. Replace some loose files with a bsa file.
1. Improve the PC fuck scene.

## 0.3.8 (2019-11-5)

1. Adds a feature that if the “reacting npc” was hostile to the doggy,it will    be hostile again only after a certain interval after it does not react to the doggy.    Notice that every time the doggy “Calling for help”, it automatically calm everybody near.    So you need to set your “Seek For Help Interval” to a value bigger than “Hostile Again Interval"    to actually see your “previous reacting NPC” being hostile again to you and maybe others     when you are still a doggy. This feature is useful for flee from the master and it is realistic    because in reality even if the master abandoned the pet the master won’t be hostile to it very soon.
1. Adds an option to slide the “Hostile Again Interval”
1. Rearrange the mcm and improve “Clean” button function.
1. Fixed a bug that when the doggy was following an NPC, and was released later,     it will remain sneak instead of standing up.
1. Fixed “doggy follow spinning bug” when the doggy was NPC,need to run FNIS again. ( It removed some animations so you’ll notice that when an NPC as a doggy turn around it    will goto valina sneak state again shortly. But at least it is not stuck in spining )
1. Fixed a bug that when the PC changes cell, the doggy sneak animation will revert to valina one.
1. Fixed a bug that even if you are not a doggy, the pickpocket line is still the doggy one.
1. Fixed a bug that when the doggy is following player, it might sandbox.

## 0.3.7 (2019-11-4)

1. Adds a “NPC Master DoDeed function” to “pc follow npc feature”. Every certain interval, the master    will stop things they are doing and try to “fix your doggy problem”.
1. Adds an option to slide the “Master Do Deed Interval”.
1. Adds a long term calm effect on the doggy’s master, so that the master won’t attack anyone until it loses its doggy. (Currently only works if the doggy is the player)
1. Adds headtrack when the pc following the master. (Found that it conflicts with “PC Head Tracking”, but     it’s not a big deal . Simply to disable the “PC Head Tracking” esp will fix this.)  
1. Remove an invalid dialogue that I forgot to remove.
1. Improve script, note that if you upgrade to this version, you should either use a clean save or click “Clean” button in debug section in mcm BEFORE AND AFTER the installation.

## 0.3.6 (2019-11-3)

1. Adds a dialogue so that you can be a pet for a different person when you “SeekForHelp”.
1. Improve few dialogue lines.
1. Fixed a bug that if you seek for help to a different person, the original “reacting” actor will still be the one who “react to you”
1. Fixed “doggy follow spinning bug” when the doggy was PC. need to run FNIS again. ( It removed some animations so you’ll notice that when you as a doggy turn around it will goto valina sneak state again shortly. But at least it is not stuck in spining )

## 0.3.5 (2019-11-1)

1. Make NPC can adopt NPC!!! ( Features not finished yet, go to download section to get the progress demo video.)
1. Fixed a bug that if you cancel follow by jump, you will follow the next reacting NPC automaticly
1. Integrates “Pose Sex” mod that I made. (The doggy will receive a secret power that after the doggy was released, it can draw other’s attention any time it want by masturbating or anything else that triggers “Pose Sex”. See the “Pose Sex Framework” link for details.
1. Improves dialogues, now it’s more immersive.
1. improves find closest function, before this improvement this function can not find actor who is too close to the player.After this improvement the function runs better (not perfect though) .
1. a new bug that when the doggy was following an NPC, and was released later, it will remain sneak instead of standing up.
1. a new bug that if the doggy was following an NPC, and the PC adopts it later, it will remain following the previous master.

## 0.4.0 (plan, written in 2019-10-30)

Fully implements the follow function and make it enjoyable (pc -> npc, npc ->pc, npc->npc ).

## 0.3.4 (2019-10-30)

1. Adds a feature to let pc follow NPC.
1. Adds a feature that when you have a master, if you try to jump, a Menu will show up and let you choose whether to leave your master,or not, or don’t ask again.If you choose “don’t ask again”, following jump will not trigger the Menu.
1. Adds functions to let the master goto Bluepalace and the Solitude Dour District if the master is in solitude.
1. Make the “immersive hello line” only spoken once in 2 hours.

## 0.3.3 (2019-10-29)

1. Adds a "Dangerous Activate “ function. It adds the curse on every door and corpse. Use infect percent in “general section" to change the curse rate. 
1. Adds an option to let you toggle the “Dangerous Activate ” function.
1. Improves sneak animations, so that when the npc turn around, the npc won’t do it in a valina way, but remain crawling.Need to run FNIS again.
1. Adds an option to let you choose whether the NPC’s seek for help line is occasional. If it’s  occasional it means the interval is 10s, otherwise it’s 3s.
1. Adds an option to let you choose whether to strip the doggy or not(default: no strip)
1. Fixed a bug that the player will “seekForHelp” to an object.
a bug that when you following an npc (in 0.3.4) or an npc following you, the doggy may get sttuck in a weird “spinning situation”. I’m trying to find out why.

## 0.3.2 (2019-10-28)

1. Adds a feature to let the doggy follow you ( through dialogue ).
1. Adds a feature that when you are a doggy, you cannot steal from others, but you have an option to “seek for help”
1. Fixed an issue that if an NPC decided to release a doggy, and you choose to interact with the doggy, the NPC will release the doggy anyway. (I allowed this, but I fix this anyway )
1. a bug that the player will “seekForHelp” to an object.
1. a bug that if you seek for help to a different person, the original “reacting” actor will
1. still be the one who “react to you”
1. a bug that when the doggy is following player, it might sandbox (interact with its surroundings ).

## 0.3.1 (2019-10-27)

1. Adds a potion which can curse you into a doggy
1. Adds a poison which takes effect on weapon, so that you can use your weapon to curse others.
1. Adds the doggy virus to dog meat.
1. Adds options to let you add them to your pocket 

## 0.3.0 (2019-10-26)

1. Adds a toggle to let you choose the “Classic Fuck Trigger” function. If this is on, you will neither be stripped nor be forced to craw.  When you sneak the npc scene will be triggered.This function bring the version 0.0.1 back to life.
1. Rearrange mcm
1. Change the option “place a dog at me” to “place a canine at me”
1. Fixed bugs that if someone in the “curse scene” is dead, the quest won’t function properly.

## 0.2.9

1. Adds Dawnguard dependancy.
1. Adds more canines (from Dawnguard): Husky,DeathHound
1. Rearrage the mcm menu.
1. Adds acknowledgement in mcm.
1. Adds a doodle in mcm. Feel free to doodle and replace the file “Data/Interface/daf_pic1.dds”

## 0.2.8 (2019-10-25)

1. You won’t stand up when you are going to have sex!
1. Adds an option to let canines come up when you are a doggy!
1. Fine tune the npc’s curse spell.

		To use this version, you need to run FNIS again.

		If you are not using a clean save, you need to go to mcm memu, click “clean” button under “debug” section.

## 0.2.7 (2019-10-24)

1. Adds the “curse spell” to an npc.
1. Adds an option to let you place a npc who has this spell at you.
1. Adds an option to let you place a dog at you.
1. Replaces the “hands off” etc. and the common hello line of npc when you are a doggy to something immersive.
1. Fixed a bug that when multiple doggies are there, if one of them died, the quest mark might not disappear
1. a new bug that even if you are not a doggy, the pickpocket line is still the doggy one.

## 0.2.6 (2019-10-23)

1. Adds the “doggy curse virus” to wolves.
1. Adds a new mcm option to let you place a wolf at your position.
1. Adds a slider to let you change the probability of infecting the virus.( default 2% , the same as valina skyrim)
1. Fixed a bug that the “calm down” function won’t work properly in 0.2.5
1. Fixed the bug “Dead but health>0 npc can react to doggy” ( this bug is rare, found when using cheat code “kill” which does not change the health of the target)

## 0.2.5 

1. adds a mcm toggle to let you choose when you are a doggy and try to stand up, if the mod make you sneak again
1. adds controller shake and camera shake when you are transforming into a doggy
1. Adds a new trap which can curse pc or npc into doggy.
1. Adds a new mcm toggle to let you add the cursedTrap at player, after that you can try it out.
1. imporve the description of the curse a little bit
1. rearrange the mcm menu
1. change the “re-sneak” interval from 0.1s to 0.7s so that you can use this short time to actually do something.

## 0.2.4 (2019-10-22)

1. Fixed a bug that if the npc  reacting  to the player died, the quest mark won’t disappear.
1. Fixed a bug that you can’t have sex with creature if you set the gender to “any”
1. Adds a new feature that if you are in front of a creature who is hostile to you, after you equip the cursed enchantment, the creature will calm down! 
1. Adds a new toggle in mcm to let you choose if you only want creatures to fuck the doggy. ( Use these 2 features to surrender to a creature and start Bestiality )
1. Fixed a bug that people’s hello dialogue became “What in the” etc. after casting the curse.
1. Fixed a bug that “clean” button in mcm won’t work properly if there are 2 doggies.
1. Improve the fuck scene, now the npc will go to the doggie first then say the suprised line.

### 0.2.5 (plan, written on 2019-10-21)

make the curse work on some trap

## 0.2.3 

1. Adds alternative sneak animation so if you are not under curse, your sneak animations are vanila ones, if you are under curse, your sneak animations are doggy ones. Require FNIS from now on. If you install this version, you won’t need  CrawOnFoursWithCameraFix.zip . The animation is the same as CrawlOnFours.
1. a new bug that if the doggy was not the PC and it changes it’s cell, the sneak animation will be reverted into valina ones. This bug is catched after 0.3.2 which enables the doggy to move around

## 0.2.2 (2019-10-20)

Adds multiple doggies function. Need a clean save to update from 0.2.1

### 0.2.2 (plan, written on 2019-10-18 )

As the modding going, I get myself into some kind of trouble so important that I must add the “multiple doggy function” or else  the modding will stop. So my plan is to do that, which might take some time.

I think there is a big chance that I will rewrite the script again.

## 0.2.1 

1. Adds voiced sound to the player ( you ) , so when you are a doggy and calling for help , you can actually hear your calling.
2. Fixed the bug under this.

	Quote

		The game can not recognize “player added enchantment” on a armor in 0.2.0. So if you put on your “fuck cursed” DD collar for example, instead of leave it be like the “cursed necklace” , the  mod will strip it. It will be fixed in the next release.

	(Supplement for 2) The new version can recognize the newly attached enchantment, however, you must drop your new item once, then pick it up. After you having done that, the game will know the new item and run normally.
	
1. Adds a mcm sex gender selection
1. Adds an option to disable follower fuck
1. Adds a slider to let you set your seek for help interval
1. Adds an slider to let you choose the maximum times npcs fuck the doggy. After the certain times of fucking, the doggy will be released. ( set to -1 to make it infinitly )

## 0.2.0 (2019-10-15)

1. Improve RaceKey underground function.
1. Improve “Doggy Fuck Curse”.
1. Improve the animation so that the doggy and the aggressor won’t need to stand up but remain sneaking (Currently this won’t affect the player ( you ), I am studying to see is there a chance to make this work on the pc ) .
1. Adds a doggy bark sound to the curse.
1. After I did something I think the “multiple strip” issue is gone.
1. Remove Player Restrainment, just make you sneak , so now you can do whatever you want, might cooperate with some DD armors better.
1. Make the “npc drop stuff” function optional.
1. Make the creature never “release the doggy” because a creature is not that smart, just the same horny.
1. Adds a new function that if you want to cancel the enchantment effect on you, you can simply unequip the enchanted item.
1. a new bug : The game can not recognize “player added enchantment” on a armor. So if you put on your “fuck cursed” DD collar for example, instead of leave it be like the “cursed necklace” , the mod will strip it. 

## 0.1.9 （2019-10-14）

1. Adds an option to let you choose “Is Find Closest NPC”. If the option is off (it is by default) , a near validated npc is chosen randomly. Otherwise the closest validated  npc to the doggy is chosen.
1. Make the “RaceKey” function work. (didn’t work from 0.09, sexlab's FindAvailableCreature function issue, I fixed it. )

## 0.1.8

1. Adds a feature, now the npc who releases you will drop one “doggy fuck cursed” armor you currently wearing. So after having been released, you need to pick up the necklace or whatever caused you to be a doggy and equip it again to restart the doggy quest. This won’t work on npc now , a pc exclusive feature. If the item is too small then it is hard to find on the ground, use your imagination to find a way to find the item more quickly.
1. Fixed a bug that if no aviliable npc there to interact with the doggy, the “seek for help” scene does not repeat
1. Adds some voiced sentence to the doggy.

## 0.1.7 (2019-10-13)

1. Makes the PC quest called “Being A Doggy”
1. Makes the npc quest a “miscellaneous” quest
1. Adds a quest mark to the npc who is going to interact with the npc doggy.
1. Fixed the issue that the quest did not appear in the “completed” quest lists.
1. Append the “IsInScene==false” condition that I forgot to add  to the spell and the enchantment
1. Improve the description of stuffs a little bit.
1. Fixed a issue that the release probability value did not work properly in 0.1.6
1. Fixed a bug that the player won’t redress after the npc release you.

## 0.1.6

1. Adds a “common doggy fuck curse” enchantment which works like before, no major bugs. 
1. Adds a “Doggy FuckCurse necklace” which works like before, no bugs.
1. Adds a “Get stuff” button in mcm so that you can get the quest items and spells of this mod if you are using a save that already enables this mod.
1. Adds a quest mark to the npc who is going to interact with you.
1. bug that the player won’t redress after the npc release you.
1. a new bug that the release probability value did not work properly
1. a bug that if no aviliable npc there to interact with the doggy, the “seek for help” scene does not repeat

## 0.1.5 ( 2019-10-12)

1. Rewrite everything.The new version has a “Doggy Fuck Curse Spell” which works like before and has no major bugs.
1. Remove “LOS” requirement of “Doggy Fuck Curse Spell” because the doggy always barks for attention
1. Remove “debug notification” button from mcm because now the mod is using trace log file completely.
1. Adds a toggle that let you choose npc’s releasing doggy probability, if set to 0 the npc always fuck the doggy, if set to 100 the npc always release the doggy.
1. Remove “constant effect” toggle because you can interfere the npc scene now. “Constant Effect” is on by default .
1. Make the sexlab arousal dependancy a soft one, so you can install this mod without SLA.
1. Adds a quest mark to  the doggy, so you can go to journal if you forget your doggy.( This also means that Doggy Auto Fuck becomes a offical quest that you can complete )

0.20 (plan, written on 2019-10-11)

		Rewrite everything and make this version works like a mod like 0.1.3 but without any bugs. Might take some time (unlike 0.0.1-0.1.3,completed in 4 days )

### 0.1.3 ( confirmed unstable ) 

1. Fixed “echantment not following” bug.
1. Can not convert the follower back correctly

## 0.1.2

1. Adds sexlab Aroused dependency. Now you can config whether the npc fuck scene aggressor depends on its arousal.
1. Now you can release the doggy (follower or not ) in dialogue.
1. Now you can fuck the doggy before an npc fucks it ( when the doggy is not following you, it should be fucked by npc if you do nothing ), when you do that the npc will get off.
1. Improve the scene ,script, debug notification.
1. new bug :The enchantment not work properly when option “is follow” is on.
1. new bug : Dispite I made the “interfere function” , in the later test I found it did not work… I think it’s ck’s fault, very confusing tool.

## 0.1.1

1. Improve the npc scene, now the aggressor will sneak too when he or she is close enough to the doggy.
1. fixed the “go back” bug

## 0.1.0

1. Improve the npc scene
1. fixed the bug “Constant Effect” doesn’t work properly 
Introduced a new bug that when the npc scene running, the aggressor will not stop at the doggy but go back

## 0.09

1. Adds a mcm config that let you input a “RaceKey” to specify a certain race that you want to have sex with.
1. Fixed the bug that won’t have sex with creature
1. fixed a bug that will unequip your power and necklace when the init.

## 0.08

1. Fixed the bug that can’t find the right sex actor.
1. Restrain the plalyer’s action ( Currently it bans you from drawing your weapon ) when wearing “Doggy curse” enchantment. Notice that “doggyAutoFuck” does not do that, It is designed to be a convinent spell different from the enchantment ( or the “Doggy curse” spell ) 
1. introduce a new bug that can’t have sex with creature ( sexlab.FindAvailableActor funcion ’s fault, not directly my fault, i am studing to find a solution.
1. introduce a new bug that After equipped the enchantment, you can’t open inventory even after the spell effect is off.

## 0.07

1. Add a mcm toggle to let you choose if you want the npc under the “doggy curse” follow you or start a scene with another npc and get fucked. If “Constant Effect” is on, the npc will be fucked again and again unless you toggle “clean” option in mcm menu. If he or she follows you, the npc sex scene will not be triggered.The default config is not following.
1. Change the enchantment name from “Doggy Attraction” to “Doggy Curse” and rewrite the description.
1. Make the curse always stripping the npc.

## 0.0.6

1. Add a dialog to the npc who is under “Doggy Curse”, which make you have an option to fuck his or her butt.
Update the necklace to make it work on player ( you ).

## 0.05

1. Add a enchanted gold necklace called “Doggy Gold Necklace”. The enchantment effect is the same as “Doggy Curse Spell”. You can learn the enchantment from it and enchant something else such as some DD collar. The enchantment is called “Doggy Attraction”. You can enchant “Doggy Attraction” to anything that can be enchanted with “light armor” enchantment
1. The necklace do not work on player character for now, give it to your follower and make sure he or she wears it.
1. From this version you don’t have to fire doggyAutoFuck to get your spell and necklace, the mod should add them automatically.   ( Comfirmed that I am wrong,I think it still need it…)
1. a bug that will unequip your power and necklace when the init.

## 0.04

1. Fixed “won’t cast” bug.
1. Add 2 mcm options, one is a toggle called “debug” , the other is called “clean” which can’t be selected actually but will take effect.
1. Add an illusion spell “Doggy Curse Spell”. If you already installed previous version, you can fire “doggyAutoFuck” again to add the spell “Doggy Curse Spell”. The spell force an npc to go into sneak state, say a bleed out word and follow you.
1. Officially added skyrim.esm and sexlab.esm dependance.

## 0.0.3

1. Improve the machanism of running. Now there is no polling. Sex should happen the instant when you fire the power and meet the condition or after you firing the power and meet the condition.
1. Forbid cast the power when having sex started by this mod.
	
## 0.0.2

added a mcm menu which introduce a “Constant Effect” toggle , added debug notice. Some bugs found, should be fixed in the future version.Currently the mcm is very simple. Just add a “ Constant effect ” toggle which will make the effect recharge forever unless you have sex wtih somebody with doggystyle triggered by this mod.
	
## 0.0.1:

basic function, adds a lesser power called “doggyAutoFuck”. After casting this power, you have 10 seconds to sneak. Once you are sneaking and the spell effect is still on, the nearest actor  who can see you will have sex with you with doggy style.
 
has a “wont cast” bug. This “won’t cast” bug exists because I did not make Skyrim.esm as its depandence so I won’t load Skyrim.esm in Creation kit. Otherwise it is too slow to load ck.

Temporary fix for the power didn’t cast :
press E to equip the power instead of left mouse or right mouse. Same as gamepad pressing A instead of RT or LT

	The power should be fired by Z ( or RB if you use gamepad) so it should be equipped by 
	neither of your hand. So a bug comes out when you do that.
​     

For friends who downloaded very early, I appologize because i made a mistake to rename the esp file without “.esp”, You can redownload it or just rename the untyped file.