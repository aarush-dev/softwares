///////////////////////////////////////////////////////////////////

Table Of Contents

Video Driver Notes
	3DFx Voodoo 2 and Higher
	3DFx Voodoo 1
	nVidia Riva 128
	nVidia TNT/TNT2
	nVidia GeForce
	Diamond Viper II
	Diamond Stealth III G540

Controls
Screen Shots
Saved Replays
Install Notes
	Poor install performance and Outlook 98
	Crash installing when using Browse on Netware Networks
Car Settings - Gear Ratios
Alt-Tab Problems
Audio Delay
NVIDIA GeForce256 and NVIDIA Quadro users
Pentium Pro and Voodoo 2 Cards

///////////////////////////////////////////////////////////////////

Video Driver Notes
Need for Speed - Porsche Unleashed was designed for use under Direct X release 7.  Please ensure that you have the latest DX7 drivers installed on your system.

The latest drivers from nVidia and 3DFx are contained in the \Drivers subdirectory on the game disc.

3DFx Voodoo 2 and Higher
Support for Voodoo2 and higher cards is through Dx7.  Please ensure that you have downloaded and installed the latest DirectX drivers for your Voodoo card.

3DFx Voodoo 1
Support for Voodoo1 is through Glide.

nVidia RIVA128
For best look and performance, the following should be set via the Nvidia RIVA 128 video card control panel:
- Per pixel mipmapping: Disabled; 
- No Automatic mipmap generation; 
- Direct3D Texture Memory Size: 0 MB.

If you are having trouble with unreadable or scrambled fonts, try changing the Addressing Mode switches to (you may need to adjust the following settings):
- Non-Filtered Texel Origin: CENTER
- Filtered Texel Origin: x=0.00 texels, y=0.00 texels.

nVidia TNT/TNT2
On the TNT and TNT2 class cards if you are having trouble with unreadable or scrambled fonts, try changing the Addressing Mode switches in the TNT/TNT2 video card control panel to (you may need to play with these settings):
- Non-Filtered Texel Origin: Upper left corner; 
- Filtered Texel Origin: x=0.00 texels, y=0.00 texels.

nVidia GeForce
Please ensure that the latest drivers are in use.  Problems have been identified with slow frame rate and game instability on driver releases prior to 5.x.

The Diamond Viper II 
This video card appears to have Z-precision issues.  This results in the polygons (or groups of polygons) appearing to "swim" and "poke through each other" in both the game options screens and while driving (most notably with the cars).  Diamond is aware of this problem and is looking into it.

The Diamond Stealth III G540
This video card has graphical problems when using some S3 provided video drivers.  Diamond provided drivers do not show this problem.

///////////////////////////////////////////////////////////////

CONTROLS
'Look Forward'
This function when used with the 'Look Left' and 'Look Right' keys allows you to look at a 45 Degree angle in each direction.   Example: When holding down the 'Look Left' key and the 'Look Forward' key at the same time, you will look left 45 degrees.   When pressing the 'look forward' button on it's own, it does nothing.

//////////////////////////////////////////////////////////////

SCREEN SHOTS
Press Alt-P to take screenshots from gameplay to show your friends or put on the Internet.   Once you have taken a screenshot, they can be found in [Need For Speed]\SaveData.  The screenshots are named UNLEASHEDxx.TGA. The file format is TGA (Photoshop)

//////////////////////////////////////////////////////////////

SAVED REPLAYS
Saved Replays can be found in the [Need For Speed]\Savedata\*.rpl directory.    You can take saved replays and send them to friends via e-mail or post them on the Internet to show off your driving skills.

//////////////////////////////////////////////////////////////

INSTALL Issues

Poor install performance and Outlook 98

Symptom
When I run Setup.exe on my system, which has Microsoft® Outlook&trade; 98 running and is connected to a Microsoft Exchange Server, the setup initialization reaches 99%, but then nothing happens. If I wait a long time, the first dialog box appears and the installation proceeds normally.

Cause
This problem occurs due to some timing issues between Setup.exe and the Microsoft Exchange Server.

Workaround
Close Outlook 98 before running Setup.exe. Generally, you should not have any other applications running when you run an installation.

Crash while installing when using Browse on Netware Networks

Symptom
On any PC with Client32 installed and connected to the network, clicking "browse" during the install to select a different directory to install to will cause the installer to crash. 

Cause
This problem happens only on some systems running Client for NetWare Networks. It is due to a bug in Nwnp32.dll that affects programs that display the 16-bit style open file common dialog box. In InstallShield installation authoring products, it affects all dialogs that contain a Browse button (AskDestPath, AskPath, ComponentDialog, EnterDisk, SdAskDestPath, SdComponentDialog, SdComponentDialogAdv, and SdSetupType).

Resolution
A fix is available on Microsoft’s Web site at http://support.microsoft.com/support/kb/articles/q192/2/49.asp. 

Note: 
This information only applies to the English version of Windows 98. Contact Microsoft for the Japanese and German versions of this DLL. 

Workaround
Prior to the availability of the fix, some InstallShield customers reported that taking the following actions enabled them to work around the problem: 

- Connect to a bindery server, instead of using NDS (NetWare Directory Services). 
- Do not map any network drives (including through the logon script). 
- Do not log on to the network. 
- Use a custom dialog to prompt for the path. 
- Use the AskPath dialog and type the path into the edit field, instead of browsing to it. 
- Install and use NetWare network client software from Novell, instead of the existing Client for NetWare Networks. 

/////////////////////////////////////////////////////

Car Settings - Gear Ratios
Gear Ratios can only be changed on Race Cars (ie: 550 Spyder, 935 and GT1) in all other cars the gear ratio cannot be changed.

/////////////////////////////////////////////////////

Alt-Tab Problems

The use of Alt-Tab to minimize the game during multiplayer Comms games may disconnect you from the game.

When returning to a game that was minimized with Alt-Tab, you may experience pauses or temporary graphic corruption.

/////////////////////////////////////////////////////

Audio Delay

If you are using a Sound Card that does not have current Direct X driver support you may experience slight delays in audio playback.

/////////////////////////////////////////////////////

Attention NVIDIA GeForce256 and NVIDIA Quadro users:

NFS:PU does not support the GeForce and Quadro cards on some Intel i820 motherboards and on some Gigabyte GA-7IX Athlon systems.  This is due to a bug in the NVIDIA drivers; the bug symptom is extremely low framerate.  The 5.x driver series from NVIDIA (which are due to be released soon) fix the problems with i820 and Gigabyte GA-7IX Athlon configurations.  

Until the 5.x drivers are released, or if you experience lockups or stability problems in general, we recommend you use the 3.77 drivers (provided by NVIDIA) which can found on this CD in the 

	Drivers\NVIDIA\GeForce256 & Quadro directory.


Please contact NVIDIA  (http://www.nvidia.com) or your board vendor for more information and release dates for future drivers based on the NVIDIA 5.x series.  

The latest NVIDIA drivers can be found at:  http://www.nvidia.com/Products.nsf/htmlmedia/software_drivers.html

//////////////////////////////////////////////////////

Pentium Pro and Voodoo 2 Cards

For users with Pentium Pro machines and Voodoo2 video cards:  if the game is not functioning at all (doesn't get into any screens) then add, "driver=voodoo2z" to your shortcut's Target: line, following Porsche.exe.  Eg.  "C:\Electronic Arts\Need For Speed Unleashed\Porsche.exe driver=voodoo2z"

