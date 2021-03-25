# Healer reactions
The project contains healer reactions for the current savage content, including a trial timeline (e5n), which can be used to get familiar with the reactions. These `Healer_RAID` timeline reactions will be executed by the `general_JOB_savage` reactions.

Additionally there can be found reactions for any other location. The `general_JOB_everywhere` reaction works anywhere apart from the optimised savage raids and the trial timeline (e5n).

Please test the reactions when using them for the first time in Trusts. This is to make sure that the files have been configured correctly and to get you first impressions about the functionality. 

Check out my other projects to use QwertCore, which is an extension to my reactions and includes many useful features.

# Requirements
[TensorReactions](http://wiki.mmominion.com/doku.php?id=tensorreactions)

# Setup
Download the latest files and open the `TensorReactions` folder. Put reactions that contain a `general` in their name into the `GeneralTriggers` folder. The other files are timeline reactions, which have to be in the `TimelineTriggers` folder.

The next steps require you to open TensorReactions inside the MinionApp menu. Choose the correct general reaction while you're on the job you want to play. At last pick the timeline of the content you would like to enter.

# How to use
For e5n/e5s/e6s/e7s/e8s/e9s/e10s/e11s/e12s you need to load the `general_JOB_savage` reaction and the `Healer_RAID` timeline. The `general_JOB_everywhere` is for any other dungeon than the previously mentioned. In conclusion the `general_JOB_savage` only works with content that has a timeline. For everything else switch to the `general_JOB_everywhere` profile.

**Examples**:
At first you would like to do e5n (e5s) with your Scholar. Load the `General_SCH_savage` reaction and the `Healer_e5n` (`Healer_e5s`) timeline. Then you decide to do an expert roulette with your Astrologian. Just load the `General_AST_everywhere` and you are good to go. At last you would like to do e6n, which also needs the `general_JOB_everywhere` profile. 

Please try to position yourself as well as possible before a mechanic happens, so that you are safely and in range of as many players as possible. Try to stand in the middle of the group as often as possible. Also make it clear to your fellow players that they should not stand at the edge of the arena if they would like to be healed.

# Hotkeys
You can also assign hotkeys to the corresponding hotbar buttons. All you have to do is open 'TensorReactions', navigate to the 'General' tab and there, in the 'Heal Gui' reaction, define either a 'key' only or a 'modifier' and an additional 'key'. Do not forget to reload lua after you have changed the reaction.
e.g. You want to press '4' to switch off the healing. Then change 'key = nil' to 'key = 52'.
If, on the other hand, you want to switch off the healing as soon as you press 'SHIFT' and '4', you change (in addition to 'key = 52') 'modifier = nil' to 'modifier = 16'.
Apart from that it is also possible to change the appearance (e.g. the size/colour of the buttons) of the hotbar in the reaction.

# Supported ACRs
**Job** | **Supported ACRs**
------------ | -------------
AST|RikuAST/SallyAST/Stargazer/MCR
SCH|RikuSCH/SallySCH/Educator/MCR
WHM|RikuWHM

# Supported content
**Content** | **AST** | **SCH** | **WHM**
------------ | ------------- | ------------- | -------------
e1s | - | - | - 
e2s | - | - | - 
e3s | - | - | - 
e4s | - | - | - 
e5s | **+** | **+** | **+**  
e6s | **+** | **+** | **+** 
e7s | **+** | **+** | **+** 
e8s | **+** | **+** | **+** 
e9s | **+** | **+** | **+** 
e10s | **+** | **+** | **+** 
e11s | **+** | **+** | **+** 
e12s | **+** | **+** | **+** 
anywhere else | **+** | **+** | **+** 


# Donations
If you would like to support me, you can do so on Patreon:
**https://www.patreon.com/user?u=48606911**
