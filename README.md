# RA01-PublicSharing-CyberPunk-VR-Injector
This is the publicly shared kit; it only contains the compiled project and none of my methodology while building it or source code.

CYBERPUNK 2077 VR
RA01 Edition
Play the whole game in real 3D VR, with your hands as your controllers.
(NO donations wanted or accepted.)



What this mod does
RA01 turns Cyberpunk 2077 into a full virtual reality game. You see Night City in true 3D, look around with your own head, and use your motion controllers as V's hands. You aim a gun by pointing it, drive by holding the steering wheel, and crouch by crouching. The whole story, including Phantom Liberty, is playable from start to finish.
It is a single, self-contained mod. You do not need any other mods to make it work (no RED4ext, Cyber Engine Tweaks, TweakXL or similar), and you do not need to install .NET or anything else.
Highlights
•     Real 3D - each eye gets its own picture, so things have proper depth and scale.
•     Your hands are V's hands - his arms follow your controllers, and his body follows your head.
•     Point and shoot - shots go where the gun barrel points, not where you look. Hold a rifle with two hands and tuck it into your shoulder to steady it.
•     Hands-on driving - grab the real steering wheel or motorbike handlebars and turn them. Press the middle of the wheel for the horn.
•     Move your body - crouch for real, climb ladders hand over hand, swim with arm strokes, throw grenades and knives with your arm.
•     Comfort first - menus, cutscene close-ups and the end credits switch to a calm flat screen in front of you, and dialogue scenes no longer swing the world around.
•     Floating HUD - health, ammo and the map sit on their own panel at a comfortable distance.
•     Left-handed mode - one switch mirrors everything, including which hand holds the gun.
•     In-game settings window - more than 180 options, each with a plain explanation when you point at it.
•     Easy launcher - finds your game (Steam, GOG or Epic), sets up VR, and puts your normal flat-screen settings back when you quit.
What you need
You need	Details
Windows 10 or 11 (64-bit)	Tested on Windows 11. Windows 10 is expected to work the same way.
Cyberpunk 2077, version 2.31	Steam, GOG or Epic. Phantom Liberty is supported. A different game version may switch some features off until the mod is updated.
A PC VR headset with two controllers	Tested on Meta Quest 3 (Link cable, Air Link, Virtual Desktop and Steam Link). Other headsets are supported but not yet tested by me - see the controls section.
A VR app ("OpenXR runtime")	Whatever your headset normally uses: Meta Quest Link, Virtual Desktop, or SteamVR. It just needs to be set as the active one.
A strong graphics card	Minimum: about an RTX 3060 Ti (8 GB). Recommended: RTX 4070 Ti (12 GB) or better. 16 GB RAM minimum, 32 GB recommended.
Installing (the simple way)
1.    Download the mod and unzip it. You get a folder called Cyberpunk2077-VR-RA01-Edition.
2.    Put that folder inside your Cyberpunk 2077 game folder (for example ...\steamapps\common\Cyberpunk 2077). It can live elsewhere and still work, but inside the game folder the launcher finds your game by itself.
3.    Start your VR app (Quest Link, Virtual Desktop or SteamVR) and put your headset on.
4.    Open the folder and run RA01.Launcher.exe. Pick your settings and press LAUNCH.
5.    Keep the launcher window open (or minimised) while you play. When you quit the game it tidies up and restores your normal flat-screen settings.
Always start the game with RA01.Launcher.exe. Starting Cyberpunk from Steam, GOG, Epic or a mod manager's Play button starts the normal flat game without VR.

Windows or antivirus warnings: the launcher is not code-signed, so Windows may say "Windows protected your PC" - click More info, then Run anyway. Because the launcher loads the mod into the running game, some antivirus programs may flag it. If yours does, add an exception for the RA01 folder.
Using it with Vortex (and your other mods)
RA01 works alongside other mods you manage with Vortex. Vortex places mod files for real inside your game folder, which is exactly what RA01 needs.
1.    In Vortex, open the Mods page and drag the RA01 download onto it (or use Install From File).
2.    Click Install, then Enable the mod.
3.    Click Deploy Mods (Vortex usually does this for you). RA01 now sits in your Cyberpunk game folder, next to your other mods.
4.    Start the game with RA01.Launcher.exe from that folder - not with Vortex's Play button.
Optional - launch from inside Vortex:
1.    On the Vortex Dashboard, click Add Tool.
2.    Point it at RA01.Launcher.exe inside your game folder and name it "Cyberpunk VR".
3.    From then on, start VR with that tool. Your other Vortex mods load as normal.
After adding or removing other mods, let Vortex deploy first, then start the game with the RA01 launcher.
Mod Organizer 2 (MO2) is not supported
Mod Organizer 2 does not really put mod files into the game folder. It shows them only to programs started from inside MO2, using a "virtual" folder. RA01's launcher starts the game in its own way (often through Steam), so the game never sees MO2's virtual folder, and the VR part cannot load properly.
If you use MO2 for your other mods, you can still use RA01: install RA01 by hand (unzip it into your game folder as in "Installing" above) and leave it out of MO2. Always start the game with RA01.Launcher.exe.
First time you play
1.    In the game's own settings, set Crouch to Toggle (needed for crouching with your body).
2.    Open the mod's settings window (see "Opening the menus" below), go to the VRIK tab and press Put camera at V's eyes, then Calibrate arms (stand in a T-pose when asked). Do this once per headset.
3.    Restart the game once. The picture sharpness settles in from the second start, because the mod first has to learn your headset's screen size.
4.    Stand or sit comfortably and press Home on the keyboard (or the Recentre button in the settings window) to set "forward" and your height.
Controls - Meta Quest (Touch) controllers
This is the default right-handed layout. Your left hand moves, your right hand holds the gun.
 
Your controller	What it does
Left stick	Walk. Click it in to sprint.
Right stick left / right	Turn. (You can also just turn your body - V follows your head.)
Right stick up / down	Nothing by default - your head does the looking. Turn on "Stick look up/down" in the settings if you play seated.
Right stick quick click	Crouch / stand (or just crouch for real).
Right stick held in + left stick	The game's D-pad buttons (there is no real D-pad on Quest controllers).
Right trigger	Shoot / attack. Hold it to charge a strong attack.
Left trigger	Aim / block.
Left grip	Quick tap: quick melee hit with a gun. Hold: scanner.
Right grip	Hold for a grenade (squeeze, swing, let go to throw).
X	Interact (doors, loot, talk) and reload. Horn while driving.
Y	Switch weapon. Hold for the weapon wheel.
A	Jump. Confirm in menus.
B	Back / cancel. Hold for 5 seconds to switch hand-gesture mode on or off.
Left menu button	Game menu (inventory, map, journal).
 

Opening the menus

Do this	Result
Hold X and the left trigger, then push the right stick up	Game menu (inventory, character, map, journal)
... then push the right stick down	Pause menu
... then push the right stick left	The mod's settings window (or press F10 on the keyboard)
In the settings window	Point your right controller like a laser and pull the trigger to click. Point at any option to read what it does.
 

Left-handed mode

Turn on Left-hand mode in the settings window (VR Controls tab). Everything swaps sides: the gun goes in your left hand, the triggers, grips and sticks trade places, and A/B trade places with X/Y. The menu shortcut becomes: hold A and the right trigger, then push the left stick.
Controls - other headsets
The mod gives each type of controller its own button layout. The Quest layout above is fully tested. The others are built and ready but have not yet been tested on real hardware - feedback is very welcome.
Game button	Valve Index	Windows MR	HP Reverb G2	Steam Frame
Move / turn	Sticks	Sticks	Sticks	Sticks
Shoot / aim	Triggers	Triggers	Triggers	Triggers
Grips (melee, scanner, grenade)	Grips	Grips	Grips	Grips (bumpers too)
X (interact, reload)	Left A	Left touchpad click	Left X	Right X
Y (switch weapon)	Left B	None	Left Y	Right Y
A (jump)	Right A	Right touchpad click	Right A	Right A
B (back)	Right B	Right menu	Right B	Right B
Game menu	Left trackpad press	Left menu	Left menu	Right Menu
Pause menu	Menu shortcut	Menu shortcut	Menu shortcut	Left View, quick tap
Settings window	Menu shortcut	Menu shortcut	Menu shortcut	Hold left View 1 s
 

•     Menu shortcut = hold the X button and the left trigger, then push the right stick (up = game menu, down = pause, left = settings).
•     Not supported: the original HTC Vive "wand" controllers (no thumbsticks). A Vive headset works fine with Index controllers.
•     Windows Mixed Reality has been removed from recent Windows 11 updates, so WMR headsets only work on older Windows versions.
•     On a new kind of controller, run Calibrate arms first. If a gun still looks tilted in your hand, please report it.
Controls that change in special situations
Situation	What changes
Driving	Put a hand on the wheel (or handlebar), squeeze the grip to hold it, and turn. One or both hands. Right trigger = accelerate, left trigger = brake / reverse. Press the middle of the wheel with your palm for the horn.
Drive-by with V's own gun	Your gun hand shoots: its trigger fires and squeezing its grip is the accelerator. Your other hand keeps steering.
Cars with built-in guns	Both hands stay on the wheel. Hold A to fire the car's guns.
The Basilisk (tank)	The right stick tilts the gun up and down. The tank uses the game's own crosshair.
Arcade machines	Pull the RT trigger to shoot (X still works too).
Braindances and taken-over cameras	The right stick looks up and down as well.
Ladders	Go up to the ladder, get on it, then squeeze a grip on a rung and pull down to climb.
Swimming	Pull your arms back to swim, sweep a hand out to turn, look down to dive.
Features you control with your body
Every feature can be switched on or off, or tuned, in the settings window.
Feature	How to do it	On at start?
Physical aiming	Point the gun itself. Shots follow the barrel.	On
Shoulder to aim	Raise the gun to your cheek and V aims (no zoom). Not used while driving.	On
Two-handed grip	Reach your other hand to the gun and squeeze its grip.	On
Virtual stock	Tuck the back of the gun into your shoulder to steady it.	On
Strong attacks	Pull a hand or two back behind your shoulder at your waist, pause a moment, then swing. Gorilla Arms: both hands up, then slam down.	On
Grenade throw	Hold the grip, swing, let go - it lands where a real throw would. (Knuckle straps recommended)	On
Knife throw	Hold to aim, then swing the knife hand forward hard.	On
Physical crouch	Crouch for real.	On
Steering	Hold and turn the real wheel or handlebars.	On
Ladders and swimming	Climb and swim with your arms.	On
Hand gestures	Switch to hands, Hold B for 5 seconds: grip = point, trigger = thumbs up, both = flip someone off(middle finger)	On
Physical reloading	Hold X for half a second to drop the magazine, grab a new one from your hip (a glowing ball shows where) and push it into the gun.	On (try it!)
Physical melee	Swing fast to strike, hold a guard in front of your face to block.	On
Laser sight	A beam from the gun barrel shows where you are aiming. (Phases through LOD by design, may change that later.)	Off
Getting the best performance
•     Open the settings window, Performance tab. It tells you whether your graphics card or processor is the limit.
•     Too slow? Lower Game resolution first (VR Video tab) - it makes the biggest difference.
•     Auto tune (VR Video tab) picks good starting values for your headset.
•     Leave ray tracing off unless you have a graphics card with 16 GB or more of memory.
•     Turn DLSS Frame Generation off - it confuses the left and right eye pictures in VR. Normal DLSS is fine.
Good to know
•     Third-person driving (the outside-the-car view, and the Basilisk) shows on the flat screen in front of you. First-person driving is full 3D.
•     Zoomed-in cutscene close-ups show on the flat screen on purpose - in 3D they felt glued to your face.
•     Game version: made and tested on 2.31. After a game update, the mod reports anything it can't find and switches that feature off safely instead of crashing.
•     Something went wrong? The folder Cyberpunk2077-VR-RA01-Edition\Logs has a file called RA01_Crash.txt - please include it in your bug report, along with what you were doing and roughly when.
•     Uninstalling: delete the RA01 folder (or disable it in Vortex). The flat game is left exactly as it was.
Credits and license
Created by Rob A. (007xSlayerx007). Free for personal, non-commercial use. Please don't re-upload it elsewhere - share the Nexus page instead. Full terms are in EULA.txt.
This is an unofficial fan-made mod. "Cyberpunk", "Cyberpunk 2077" and all related names and logos are trademarks of CD PROJEKT S.A. This mod is not made, sponsored or endorsed by CD PROJEKT. That said, I do appreciate and love CD PROJEKT RED, and find it poetic that Cyberpunk2077 released 1 year before in real life VR exploded, AI, and brain chip interfaces, like Neuralink. Simply uncanny and very cool that.

Up next is a full 6 DOF VR mod of Mass Effect Legendary Edition. Stay tuned.
