# Sigma Strike
 Sigma Strike: a TechnoBattle Game
 
Sigma Stike v 0.3 - Open Alpha.

Thanks to everyone who responded to the call and was able to test the previous version of Sigma Strike.
I have a new build for you and it is now available for everyone. You can access it via the Github: 

Play it this weekend and let me know what you think, what options are missing and what should be redone.

Thanks u/Robocop613 who helped me in creating Discord server. You are welcome to join and test and discuss the project development there: https://discord.com/invite/ZTVxpH2Q 

Any feedback is welcome, you can post it here or in Discord.

Notes:
The game is not finished. It is full of bugs, not stable and sometimes breaks. All this can lead to frustration. If you want to download it to enjoy the game, don't. This build is only for those who can help in development with their feedback.
Rule of a thumb - do not spam buttons and let AI finish what he is doing. I haven't had time to put in the foolproofing or test edge cases right now.
When you load the game, a random Lance of 4 mechs will be created for you (about 150 points per AS rules). The random Lance will also be given to the AI. 
The map is randomized every time you start the game again.
Ideally, each game will be a new game with new mechs on a new playing field.
There are four circles under your mech - the white one marks the radius you can walk, others define shooting ranges.



Change list:
Added Critical Hits. The game instantly became more fun. For clarity, I replaced the term “MP” with “ Leg Crippled.
As per requests from previous feedback: 
Exit game button added
When switching between characters, it is now impossible to go to the second round. if you have moved a mech, you can't go back to it.
We now have 20 IS mechs of the Clan Invasion era. Each costs ~35 PV, so the randomized lances should be balanced. 
AI improved using AS: Aces mechanics (still not final, but much better)
Added ways to move - you can sprint at the cost of losing the ability to shoot, you can remain stationary for better aim losing your TMM. Jumping is not possible yet.
You can now change the livery of your and enemy mechs (the colors list is still buggy and reflects not the current choice but the latest)
The following abilities were added: CASE, ENE, AMS, LRM/SRM/AC (no alternate munitions yet), OMNI
A lot of under-the-hood improvements to code and UI.

Known issues:
Ignore the falling Madcat at the beginning of the game - this is Kerensky leaving the Inner Sphere. Let it fall and disappear, then press the button to switch to the next mech. The game will start.
Navmesh does not dynamically calculate collisions, so mechs do not see other mechs as obstacles and can bump into each other.
There are no firing arcs yet. You can 360 no scope, and there is no bonus for attacking enemy mech from the rear.
