---
title: Troubleshooting
layout: home
nav_order: 6
---

 
# FAQ & Common Issues

## My game won't start even after a fresh install!
Check in your `Tahrovin\Stock Game` folder for an `openvr_api.dll` file. If this file is not present, your game cannot start. To solve this, copy the `openvr_api.dll` file from your Skyrim VR Steam installation folder into your `Tahrovin\Stock Game` folder and relaunch.

When using ENB Organizer, **always** disable an option *then* enable another. Not doing this will mess up the files.


## There's a black square / weirdly textured square in the middle of my view
Press END to open the Skyrim Upscaler menu and toggle TAA off and then back on again, the square will go away after this. It may or may not come back next session, just follow the same steps again.
If it's coming back too often, you can prevent it completely by just keeping TAA off in the upscaler menu.

## I get an OpenComposite error when launching the game?
Like this?

![](https://i.imgur.com/3zYQXNz.png)

If you are getting an error message like the screenshot when launching the game, you have OpenComposite enabled for a non-Oculus headset or you are using VirtualDesktop. Disable OpenComposite, enable SteamVR.

## I Crashed!
Giving me that little info is not helpful. 

Make sure you excluded your Tahrovin folder in your antivirus software. If you use an aggressive antivirus package such as Webroot, Bitdefender, Avast etc etc, I urge you to get rid of it and just use Windows Defender.

Please upload (drag and drop the file into the `#tahrovin-support` Discord channel) the most recent crash log from your `Documents\My Games\Skyrim VR\SKSE` folder.

If you have modified Tahrovin, ignore the previous advice and keep to the `#tahrovin-modifications` Discord channel. I will not help you with modified lists in official support categories - less because I don't want to and more because I cannot.

## Where's my UI?
Raise your left hand, palm facing upwards, to activate the compass and your stat bars. Raise your right hand in the same way for your needs bars. If you wish, equip the soul gauges in your inventory and assign them to stats. When it asks for hand offset, I recommend you set the offset to **3**.

## Is there a way for me to see myself?
Go to the VRIK MCM and Activate the Selfie mode. Then, raise your right, left, or both hands above your head depending on your choice and rotate your wrist to turn your character. If you put your hand down, your character should stay in selfie mode - re-raise your hand to disable.

## How do I change my or an NPC's body?
Obody. Default VRIK gesture is Right Thumbstick click + Controller Down. Want to change the Obody gesture? [Read this.](https://github.com/iAmMe27/Tahrovin/wiki/Changing-Autobody-Hotkey)

## Playing in Seated Mode
Tahrovin features the `Auto Sneak and Jump` mod which relies on your movement in real life to jump and crouch, therefore making it not very useful to you if you prefer to play in seated mode. Unless you'd like to try sneaking everywhere you go, you should be fine to disable this mod from the "Gameplay Mods" section in MO2.

## Loading takes too long!
Shouldn't have put the modlist on a HDD - I did warn you earlier in this very readme.

## I have grey hands/Vive wands in game!
Create a new file in the Stock Game folder and name it `opencomposite.ini`. In that file, write a single line consisting of:

`admitUnknownProps=true`

Save, close, relaunch game.

## My settings keep reverting!
Changing your settings while ingame doesn't work well. It changes a whole bunch of stuff besides what you wanted to change. I would recommend doing it manually by editing the skyrimprefs.ini file in your profiles folder with a text editor. If you know what you're doing, you can simply remove the read-only attribute on that file to allow usage of the in-game settings again.

## I can't block!
The vanilla SkyrimVR method of blocking (holding a shield in front of you, or holding a weapon sideways), is disabled by default in favor of pseudo-physical parrying. If you are trying to use vanilla SkyrimVR blocking, first make sure you have enabled it in the optional Blocking/Parry mods. If you have and it's still not working, delete 'SkyrimCustom.ini' in 'Documents\My Games\Skyrim VR' 

## I can't move!
You started Tahrovin before making sure your controllers were connected. Restart the game.

## I CTD on launch!
Well, that could be a multitude of things. Make sure you Tahrovin folder is added to your antivirus exceptions/allow list and try again.

If you have some heavily aggressive antivirus program such as Webroot, Bitdefender etc, get rid of it.

If you have a non-RTX Nvidia GPU, I ask you to refer to the [DLSS/FSR/XeSS](Installation.html#dlssfsrxess) section again.

## Can I add XYZ?
I don't know, can you?




