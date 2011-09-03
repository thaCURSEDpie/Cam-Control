//////////////////////////////////////////
// 		Mod Name: 	Camera-Control
//		By:			thaCURSEDpie
//		Date:		2010-05-15
//		Version:	0.1 BETA
//		Description:
//			Control the in-game camera :)
//			- no-clip through the city
//			- adjust FOV
//			- adjust roll
//
//		Read the license!
//////////////////////////////////////////


//Installation:
///////////////
Extract all files and folders to your main GTA:IV / EFLC directory.

You will need:
An ASI-loader  
(http://www.gtaforums.com/index.php?showtopic=380830)

HazardX's .Net scripthook 
{http://www.gtaforums.com/index.php?showtopic=392325)

.Net framework 4 
(http://www.microsoft.com/downloads/details.aspx?FamilyID=9cfb2d51-5ff4-4491-b0e5-b386f32c0992&displaylang=en)

Visual C++ library 2010 
(http://www.microsoft.com/downloads/details.aspx?FamilyID=a7b7a05e-6de6-4d3a-a423-37bf0912db84&displaylang=en%C2%A0)


//Usage:
////////
Press F4 (default) to enable the Free-Cam. This allows you to 'no-clip' through the city.
Once you have activated the camera you can:
-increase the FOV		(default: F5.		max: 170 (or it crashes :P) )
-decrease the FOV		(default: F6.		min: 3)
-increase the roll		(default: F7.)
-decrease the roll		(default: F8.)

to move around:
W/S:		Forward/Backward
A/D:		Strafe left/right
Q/E:		Upwards/downwards
mouse:		Look around :)
Arrow keys: Look around


//Advanced:
///////////
You can change all settings in the provided .ini.

The settings with a brief description:
Setting:				Description:							Default:

forwardKey 			Key used to move the camera 				Keys.W
backKey 			Key used to move the camera backward		Keys.S
rightKey 			Key used to strafe to the right				Keys.D
leftKey 			Key used to strafe to the left				Keys.A

strafeUpKey 		Key used to look up							Keys.Up
strafeDownKey 		Key used to look down						Keys.Down
strafeLeftKey 		Key used to look left						Keys.Left
strafeRightKey 		Key used to look right						Keys.Right

upwardKey 			Key used to go upwards						Keys.Q
downwardKey			Key used to go downwards					Keys.E
sprintKey			Key used to move faster						Keys.ShiftKey

incFov 				Key used to increase FOV					Keys.F5
decFov 				Key used to decrease FOV					Keys.F6

incRoll 			Key used to increase roll					Keys.F7
decRoll 			Key used to decrease roll					Keys.F8

forwardMult 		Affects forward speed						0.5
backMult 			Affects backwards speed						0.5
leftMult 			Affects left speed							0.5
rightMult 			Affects right speed							0.5

upMult 				Affects upward speed						1.0
downMult			Affects downward speed						1.0

strafeLmult 		Affects left look speed						3.0
strafeRmult 		Affects right look speed					3.0
strafeUmult 		Affects up look speed						0.05
strafeDmult 		Affects down look speed						0.05
sprintMult 			Which multiplier to use when SPRINT			4.0
					is being pressed
mouseXmult 			Multiplier for mouse movement in X-dir		140
mouseYmult			Multiplier for mouse movement in Y-dir		2.0

fovMult				Affects multiplier change speed				1.0
rollMult			Affects roll change speed					1.0

loadTest 			Used to check if settings load successfully (dont touch!)


//Contact:
//////////
Contact me @gtaforums.com: my nickname is: "thaCURSEDpie"


// License
//////////
This software is provided 'as-is', without any express or implied
warranty.  In no event will the author be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use redistribute this software 
freely, subject to the following restriction:

The origin of this software must not be misrepresented; you must not
claim that you wrote the original software. If you use this software
in a product, an acknowledgment in the product documentation would be
appreciated but is not required.  
