# Ori DE TAS
Tool Assisted Modification for Ori and the Blind Forest DE with Rerecording

Original TAS tool can be found at https://github.com/ShootMe/OriDETAS

This modification uses [XInputDotNet](https://github.com/speps/XInputDotNet)

Open Ori in your Steam directory (usually C:\Program Files (x86)\Steam\steamapps\common\Ori DE\)

### Setup
	Copy Assembly-CSharp.dll, OriDETAS.dll, and XInputInterface.dll to (Ori DE\Ori_Data\Managed\) from the above directory.
	
	Make sure to backup the original Assembly-CSharp.dll before hand.

If you are going to playback a TAS file that is already created copy the file to (C:\Program Files (x86)\Steam\steamapps\common\Ori DE\) and make sure it is named 'Ori.tas'
Otherwise the program will record a new file there in it's place.

### Controls
1. To playback already recorded TAS
	* Left Trigger + Right Trigger + Right Stick Button
	* KB: B
2. To record completely new TAS
	* Left Trigger + Right Trigger + Left Stick Button
	* KB: N
3. To stop playback/recording
	* Left Trigger + Right Trigger + DPad Down
	* KB: J
4. To start rerecording during playback
	* KB: Backspace
5. KB Only (Frame rate and slowdown methods not recommended)
	* R to decrease speed
	* T to increase speed
	* G to set back to normal speed
	* F to frame step
	* Shift + B to reload tas file
6. While playing back or recording:
	* To frame step forward one frame - DPad Up
	* While frame stepping hold Right Analog Stick to the right to frame step continuously
	* To continue playback at normal speed from frame stepping - DPad Down
	* When not frame stepping move Right Analog Stick to slowdown or speedup playback
	* To reload TAS file (after you make edits) - Left Trigger + Right Trigger + DPad Up
	* You can also frame step with the Guide Button (XBox Button)


### Valid inputs in Input File (Ori.tas)
1. Jump
2. Esc: Input to cancel options/menus
3. Action: Input to accept options/menus
4. Dash
5. Grenade: Ori will shoot light grenade
6. Save: Ori will start to save (Soul Link)
7. Glide: Feather. Also same input for grabbing objects
8. Fire: Sein will attack
9. Bash
10. Start: Input to pause the game
11. Select: Input to pull up the Map
12. CJump: Charge Jump
13. UI: Will toggle the UI on/off (UI always starts on when you first start playback)
13. Left: X Axis all the way the Left
14. Right: X Axis all the way the Right
15. Up: Y Axis all the way Up
16. Down: Y Axis all the way Down
17. XAxis,0.000: Specifcy X Axis directly (-1.000 to 1.000) (Left to Right)
18. YAxis,0.000: Specify Y Axis directly (-1.000 to 1.000) (Down to Up)
19. Mouse,0.000,0.000: Specify mouse position directly (0.000 to 1.000) (0,0 being Top Left and 1,1 being Bottom Right)
20. DLoad: Loads from the current save point (Same functionality as Load in Debug menu)
21. DSave: Creates a new debug savepoint
