------------------------------------------------
Getting quite 'annoyed' by now, by people which keep adding "issues" to "ask" for functions they want in THEIR script, READ THE DOCUMENTATION before even considering to openining an issue! This Resource DOES NOT save, manage or limit level perks etc! It doesn't even store levels/xp! It's "JUST" an graphical interface.
------------------------------------------------


Basic Information:
 What is it: This is a FiveM scripts which gives you the ability to use the normal
 ingame Rank/XP Bar to use in your own gamemode/server.
 
 My scripts supports several function calls like for example
 the first 'init' when spawning:
 ![alt text](https://github.com/VenomXNL/XNLRankBar/blob/master/ScreenShotExamples/InitialSetupDuringSpawn.gif)

Also supports rankbar animation when gaining multiple levels at once:
![alt text](https://github.com/VenomXNL/XNLRankBar/blob/master/ScreenShotExamples/MultipleLevelsUpAnimation.gif)

And as extra addition it also supports taking away XP (with a red color),
which can for example be used when an server admin uses an "XP punishment":
![alt text](https://github.com/VenomXNL/XNLRankBar/blob/master/ScreenShotExamples/TakingAwayXP.gif)

<b>KNOWN 'ISSUES':</b>
- It CURRENTLY doesn't support to color the 'globes'/level circles (except the normal color blue)
- When ranking 'down' (taking away XP) it doesn't animate the 'level globes' (and i don't care for that either :P)

<h1>
	Script License and Usage
</h1>

This script has been fully written from scratch by VenomXNL
FiveM Account: https://forum.fivem.net/u/VenomXNL/

I've spend a sh*tload of time on research to get it to function like
I wanted (near original game style), spend lots of time on trial 
and errors, and even debugging the original game to be "100% certain"
of the correct parameters. So PLEASE have decency and respect the
small 'requests' in my license :) 


I won't put up all kinds of MIT, CC or what ever licenses etc here for
you to read and/or understand. Just some basic 'rules' which count as
my license and license limitations:

Limitations, You:
 - CAN NOT Claim that this script is yours or that you've made it
 - CAN NOT Make a small adaption and call it an "improved version" or "updated version"
 - CAN NOT EVER sell this script or include it in 'sold bundles'
 - CAN NOT Redistribute it elsewhere (I MYSELF will maintain the latest release version on MY github)
 - CAN NOT Re-upload your 'own version' without WRITTEN permission on my FiveM account!
 - CAN NOT Use it on servers which violate the FiveM ToS about making profits! (Yeah, aint I a bitch? :P)

However:
 - You CAN Implement it in your own game-mode/server
 - You CAN adapt/change it (OBVIOUSLY) to your own needs for your server (just NO re-uploading without permission)
 
 <h1>
	Implementations into frameworks (Like ESX, vRP, EssentialMode or whatever is out there)
 </h1>
 So we can't redistribute it into our framework without permission?
 Yes you CAN implement AND redistribute it into frameworks, altough I would HIGHLY appreciate
 it that you would send me a message (PM or so) that you are using it in your framework so
 that I know that my script is of good use and being a useful resource
 
 What is MANDATORY though when implementing it in frameworks like ESX, vRP or any other,
 is that you DO PUT THE APPROPRIATE credits in the code at my rankbar scrip section(s)!

<h1>
	Implementations or 'moduled versions' for gamemodes
 </h1>
 I'm I for example allowed to "just make an ESX version" as 'addon' for ESX and then
 publish it for ESX users?
 
 NO! You will NEED PERMISSION to do so! 
 WHY? Well simple: Since I want to prevent the forums and releases section from flooding
 with all kinds of 'alternate versions' of my script like for example:
 - XNLRankBar (original)
 - XNLRankBar [ESX Addon]
 - XNLRankBar [vRP Addon]
 - XNLRankBar [EsMode Addon]
 - XNLRankBar [MyFramework Addon]
 
 etc etc etc,
 
 This will just causes a freaking mess on the forum and impossible to decently
 maintain script. So IF there is (ENOUGH!) need/requests for an addon for one of the
 frameworks (and the framework itself doesn't want or refuses to implement it) THEN
 ONE other developer/scripter can get permission to adapt the code to make it compatible
 for that framework, but ONLY ON REQUEST.
 
 <h1>
	Q&A
</h1>
 Q: Will you (VenomXNL) make 'alternate versions' to support frameworks like ESX, vRP etc?
 A: NO I WILL NOT, I Do NOT use frameworks myself (I'm developing my OWN 100% 
    custom server from scratch with my own (non-released) 'framework'. And thus I have no
	interest in installing other frameworks or scripts to test adaptions.
	When i would do this i would need to either:
	 A: Install a 'massive framework' and run it without knowing what the code's actually do
	 or B: Install the framework and read all code so i know what runs on my server.
	So NOPE, not going to happen, When I write, run or test code I want to know 100% what 
	that code does, or even better: have written it > 99% by myself.

 Q: Why are you so strict on 'the license' and usage?
 A: Well basically i'm not strict, you can use it, adapt it, use it on your server etc etc,
    You just can't 'steal the code' and take credits, profits or any other 'common sense abuse' of it 
	IF you think those 'limitatations' are 'unfair' or 'to strict' then you are proberbly not
	having the 'correct intentions' with code written by others ;)

 Q: Why do you have so much comments in your code?
 A: To make sure it is well documented and explained as clearly as possible, so it's usable for
    "all levels" of scripters (from beginner to advanced). And also in the HOPES to get more 
	beginners interested in coding due to them actually understanding what it does and thus
	them actually learning scripting themselves to :)
	
 Q: You seem to limit 'extra versions' for frameworks, do you have something against frameworks?
 A: Well... euhm.. yes and no... :
    I don't mind frameworks, don't mind basic toolsets to make a basic setup/startup.
	What I DO mind is that so many people install sh*tloads of frameworks and addonds for them
	without understanding the most basic aspect of scripting in games like these.
	
	The issue I have with that is that it often causes issues, people complaining about conflicts
	and script problems and 'admins' running servers without actually knowing what the server and or
	scripts do on their server.. And then the part that AWESOME scripts are made but only are compatible
	with "sh*tloads or requirements" like entire frameworks for just a "simple small extra function".
	
	I would rather see scripts being developed in the style like this one for example, where the script
	has it's own "OnPlayerEvent" functions that are called so that everyone can use them.
	
	So NOPE i don't have anything against frameworks, but DO have something against the way how many people
	use them without knowing a single bit of coding and then complaining at the developers about conflicting scripts
	and due to that lots of scripts flooding the forums with 'alternate versions' to "fix an issue" which isn't even
	an issue when the script would just be made "universally compatible"
	
