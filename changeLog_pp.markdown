---
layout: page
title: Public Plaything
permalink: /PublicPlaything/
---

## Public Plaything Changelog

### 0.0823(2-1-2021)

1. Make the stalker stop assaulting if player is in combat 
2. Make player's current dialog menu cancelled if stalker start assaulting  
3. Fix a bug that when recover from the scene, if player is using a weapon, the player won't be able to sheath
4. Won't select any character who is in sex animation as a stalker

### 0.0822(11-29-2020)

Fix a bug that the assault might not get restarted.

Correct the info in the MCM description. Fix some other minus bugs.



### 0.0821(11-26-2020)

Separate huan's skse plugin from Public Plaything. No more mouse issues and dialog menu.

Add some explain text in MCM.



###### 0.082 (10-25-2020)

fix all the bugs in 0.08

## 0.08 (10-24-2020)

Dynamic Dialog Supported! It's done by a new SKSE plugin.

You can read Data/PublicPlaything/1_Babo.json and Data/PublicPlaything/2_Huan.json to see how I've done it. Make your own action!

| page1                                                        | page2                                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| <img src="/myassets/img/pp_0.08_log_pic1.png" alt="img" style="zoom:50%;" /> | <img src="/myassets/img/pp_0.08_log_pic2.png" alt="img" style="zoom: 25%;" /> |



## 0.072 (10-19-2020)

Fixed a bug that the cooldown time doesn't work. fix a dialogue.

## 0.071 (10-15-2020)

Along with the bug fix, there's also a new "Toggle Translation" button in 0.071. Sometimes( most of the time actually) the NPC clips with PC when translating. But it's not perfect either to disable it because then the NPC will teleport to you. I'll see what else I can do.

## 0.07 (10-13-2020)



| (nsfw, it's at myassets/img/pp_0.07_log_pic1.png)            | (nsfw, *2.png)                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| <img src="/myassets/img/pp_0.07_log_pic3.png" alt="pp_0.07_log_pic3" style="zoom:50%;" /> | <img src="/myassets/img/pp_0.07_log_pic4.png" alt="pp_0.07_log_pic4" style="zoom:50%;" /> |


Alright! The full JSON customization and 3 actions from Yuni have been implemented successfully! 


Public Plaything could do many things with customization support. Right now all the actions have multiple dialogs that lead to a different ending. You can also click the mouse button to finish the struggle bar or wait and see what will the assaulter do next! (Depending on the JSON file, some actions might not have a strugglebar)

PP requires SexLab, JContainer, and UIExtension currently.

You need to run FNIS again.

Start testing some of the actions by using the "Public Plaything Menu" lesser Power in the magic menu.

You can customize your JSON file! I've made a manual for you. Files are saved in Data/PlublicPlaything.

Every time you open up the "Public Plaything Menu" lesser power, the mod automatically reloads all the JSON files.



## 0.06 (10-06-2020)

I finished the framework, and implemented dialogues on the existing two action, the borrowed one and my "grope ass and feet" one.

I suggest you try the mod first to feel the big change.

You can adjust the talking interval in MCM and assaulted gender in the lesser power.

I didn't have time to make new animations. It is left to the next version.

The new version gives you the whole idea of the mod.

You can get harrassed with natural dialogues shows up.

Sometimes the assaulter speaks by himself and you can't answer him.

Sometimes you two interact with each other and lead to a different ending.

Struggle bar may push the assaulter away, but it might show a dialog

If you didn't finish the struggling bar, the action might proceed, but might not a dialogue might show up instead.

In the "grope" action, you can take off your clothes and shoes though the dialog, if you are willing to.

(one of the animation got terribly wrong that the assaulter's spine get tweaked. I'll absolutely remake this one)

## 0.05 (9-1-2020)



<img src="/myassets/img/pp_0.05_log_pic1.jpg" alt="img" style="zoom:50%;" />

<img src="/myassets/img/pp_0.05_log_pic2.jpg" alt="img" style="zoom:50%;" />

<img src="/myassets/img/pp_0.05_log_pic3.jpg" alt="img" style="zoom:50%;" />

It's my new mod, previously called Huan's Sneaky Stalker.

If you choose "stalk" mode, NPCs will stalk you randomly, and try to grope you. Once you get rid of him by reducing the strugglebar to zero by clicking left and right button repeatedly , you'll have a chance to escape if you have the "assaulter could give up" option on.

If you choose "openly flirt" mode, NPCs will not be sneaky, but will flirt you directly.

There are different assault action types, I call them "Assault Action ID". Different assault types might have completely different animations, branches and results. Test them with the debug lesser power menu which could be removed by the MCM menu.

It requires PapyrusUtil which is installed if you have SexLab installed, UIExtension, SkyUI, SKSE, Currently it won't trigger SexLab, so it doesn't depend on sexlab right now.

Need to run FNIS.