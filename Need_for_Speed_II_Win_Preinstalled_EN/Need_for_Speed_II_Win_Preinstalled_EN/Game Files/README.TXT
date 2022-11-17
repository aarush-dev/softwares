                              Electronic Arts(R) presents
                                 NEED FOR SPEED(TM) II


                           MANUAL AND REFERENCE CARD ADDENDUM



WHAT THIS FILE IS
================
This file contains information which became available after the manual and reference card 
were printed. If you are experiencing problems not covered in the Reference Card or in this 
README, please contact EA Customer Support (see contact methods in the Reference Card).




******************************************************************************************

  					ADDENDUM

******************************************************************************************


SYSTEM REQUIREMENTS
===================
Some information printed in the reference card is incorrect. The following is the accurate
system requirement list which matches the label on the box:

SYSTEM REQUIREMENTS
Operating System: Windows 95
CPU Type & Speed: 90MHz Pentium Class processor (Intel, Cyrix 6x86)
Hard Drive Specs: 10 MB free space for game plus space for save games (additional space
   required for DirectX 3.0 installation)
Memory: 16 MB RAM
CD-ROM Speed: 4x CD-ROM drive (600 KB/second transfer rate)
Other Needs:
   * DirectX 3.0 (included on game CD)
   * Hi Color (65,535 color) capable 1 MB PCI video card with DirectDraw 3.0 compatible
     driver
   * Keyboard
   * Optional joystick or mouse
   * Optional Sound Card with DirectX compatible sound driver
Supported Input Devices: Any analog joystick, steering wheel, or game pad supported by 
   Windows 95 including but not limited to: ThrustMaster T1 and T2, CH Products Virtual
   Pilot and CH pedals, CH Products Force FX, Gravis GamePad, Microsoft SideWinder game
   pad, Extreme Competition Controls

REQUIRED FOR MULTI-PLAYERS
* Network (2-8 players): Pentium 133 MHz CPU or faster, IPX compliant network,
  1 CD per network game
* Modem (2 player); 100% Hayes compatible 9600bps or faster modem; high speed serial
  port (16550 UART)
* Serial play (2 player): null modem cable, high speed serial port (16550 UART)

RECOMMENDED
* Pentium 166 MHz CPU or faster
* Hard Disk: 70 MB free space for game plus space for save games (additional space
  required for DirectX 3.0 installation)
* Mouse
* Analog joystick, PC game pad, or PC steering wheel
* Sound Blaster 16/32/AWE32 sound card


NETWORK PLAY ADDENDUM
=====================
* In the chat screen, you can clear your chat box completely by pressing the HOME key on 
  your keyboard.

* DirectPlay IPX is not supported by Need For Speed II. To play a network game, use the 
  WinSock IPX protocol.



FORCE FEEDBACK SUPPORT
======================
Need For Speed II includes support for the Immersion Corporation "I-Force" force feedback 
driver and the CH Products ForceFX joystick. The I-Force driver is automatically copied to 
your Need For Speed II directory during game installation. Future force-feedback devices 
which use the "I-Force" driver should also be supported, although we have no way of 
guaranteeing compatibility with future controllers. 

Ensure your joystick is configured properly under Windows 95, all joystick cables are 
properly attached, and run NFS II. From the main menu, select OPTIONS, then CONTROLS, and 
then FORCE FEEDBACK. A message saying "Auto detecting" will appear and the game will look 
for your force feedback joystick. The message "Device not found" appears if the joystick is 
not detected - double-check your joystick configuration in Windows 95 is correct and try 
again. 

If the joystick is detected, the force-feedback sensitivity menu will appear. Use your mouse 
to select the force level you desire; maximum force is exerted when the bar is all the way 
to the right, and all forces are disabled when the bar is all the way to the left (select 
this level if you want to use your force feedback controller as a normal analog joystick 
without any forces). You should notice some resistance on the joystick as you change the 
effects level. As soon as you begin playing, you should notice the effects immediately. If 
you do not, double-check your settings and effects level.


CONTROLLER CONFIGURATION
========================
* If you attempt to configure your controller (ie: joystick, wheel, pedals) in the 
  CONTROLS setup, it's important that you keep the joystick or wheel centered and not 
  depress the pedals; doing so can cause the controller to perform in a reverse manner.

  Make sure that you have the pedals in the full up position (off gas) when you select 
  to map a pedal as a control (ie: ACCELERATE or BRAKE).  If you have the pedal depressed 
  when you try to map it as either ACCELERATE or BRAKE (and then release the pedal to map 
  it), then the pedal will have a reverse effect in gameplay.  (ie: releasing the pedal 
  with your foot will act as acceleration, while depressing the pedal will let off the 
  gas).

  Make sure that you have the steering wheel in the center position when you select STEER 
  LEFT in the CONTROLS setup menu and then move the steering wheel to the left to map it 
  correctly.  If you are holding the steering wheel to the left when you click on the STEER 
  LEFT selection, and then release the steering wheel, this will result in your steering 
  wheel being mapped backwards in gameplay (ie: Steering Left with the steering wheel in 
  gameplay will result in your car steering more to the right).

* An ANALOG/DIGITAL toggle option has been added to the CONTROLS menu. The default setting
  is ANALOG. If you have a digital controller, change this option to DIGITAL. This will 
  give you better control when driving with a digital controller.

* The STEERING SENSITIVITY option has no effect if steering is mapped to a keyboard or
  joystick buttons.


THRUSTMASTER T1 AND T2 WHEEL CONFIGURATION
==========================================
ThrustMaster T1 and T2 users may experience control problems in the game or front end as a 
result of Windows 95 driver problems. This can be resolved by using a special JOYCAL.EXE 
program which is automatically copied to your hard disk during game installation. To 
correct these problems, do the following:

1. Install Need For Speed II.
2. Configure your T1 or T2 using the Windows 95 Joystick control panel (please refer to
   either the Windows 95 documentation or your controller manual for details).
3. Using either Windows Explorer or an MS-DOS Prompt shell, change your current directory
   to where you installed NFS II (the default installation directory is 
   "Electronic Arts\Need For Speed II").
4. If using Windows Explorer, click on the "JOYCAL.EXE" icon. If using an MS-DOS Prompt,
   type "JOYCAL.EXE" and press RETURN.
5. A simple controller configuration screen will appear, with two horizontal bars stacked
   on top of one another. Move your wheel all the way to the left and right, and press
   your gas and brake pedals down completely one at a time. The small white blocks in each 
   horizontal bar should now be centered within the bar (it is acceptable for them to jitter 
   a little).
6. Press a button on your T1 or T2 to exit JOYCAL.
7. Play NFS II. Any previous problems experienced should no longer occur.

NOTE: If you stop using the T1 or T2 (ie: start using a joystick instead), be sure to delete 
the file JOYCAL.CFG from your NFS II root directory. NFS II looks for this configuration 
file at runtime, and if present, uses the controller configuration information stored in it
instead of the information supplied by Windows 95.



MODEM COM PORT
==============
Need For Speed II will auto detect your modem's COM port.  However, Need For Speed II may 
have difficulty detecting your modem's COM port if you are using a Plug and Play modem.  If 
this is the case, you will have an option to manually select your modem's COM port after you 
click 'Dial' or `Answer'.  Need For Speed II will remember this COM port setting until you 
exit to Windows 95.  You will have to manually enter your modem's COM port again the next 
time you run Need For Speed II.  If you are unsure of which COM port your modem is on, you 
can find out this information by following these steps:

- Left click on the START button, and move your mouse pointer over the SETTINGS item.
- When a submenu appears, select CONTROL PANEL.
- Double click on `Modems'.
- Select your modem and click `Properties'.
- The modem's COM port will be displayed here

If you open 'Modems' from the Control Panel and cannot locate your modem, you need to 
install it in Windows 95 first before using it in Need For Speed II.  Contact your modem 
manufacturer if you are having difficulty installing your modem in Windows 95.


AUDIO ADDENDUM
==============
* An INTERACTIVE MUSIC option has been added to the AUDIO menu which can be toggled ON and
  OFF. Turning this option ON allows interactive racing music to be played during the game
  (each track's racing music is temporarily copied to your hard disk for that race, and
  could increase track load times up to 30 seconds); you will be notified if you have
  insufficient hard disk space to turn interactive music on. Turning this option OFF will 
  instead use normal non-interactive music played from the game disc (songs are not copied 
  to the hard disk, nor are load times increased). This option is set to OFF by default.




******************************************************************************************

					TROUBLESHOOTING

******************************************************************************************


MODEM PROBLEMS
==============
* Need For Speed II relies upon the modem settings you set in the Windows 95 Modem control 
  panel. If you need to adjust your modem's settings, you will need to do so in the Modem 
  control panel. Please refer to your Windows 95 manual for further details on how to 
  configure a modem's settings using the Modem control panel.

* To disable Call Waiting, enter the appropriate code (usually *70 or 70#) before the 
  telephone number in the modem phone number list (ie: *70-123-4567). In certain instances, 
  particularly in an office environment, you may need to enter a "9" before the telephone 
  number if you must access an outside line (ie: 9,123-4567); contact your telephone system 
  administrator for exact details.


NETWORK PLAY PERFORMANCE PROBLEMS
=================================
The following can help improve performance during network games:

* The host system MUST be the fastest system participating in a network game (see
  SYSTEM REQUIREMENTS section above).

* Performance will improve on systems with additional memory above the minimum requirement
  (ie: total of 24 MB or 32 MB RAM).

* Turn racing music OFF in the AUDIO submenu (from the main game menu, select OPTIONS, then
  AUDIO).


VIDEO & GRAPHICS PROBLEMS
=========================
* The Diamond Viper Pro 2MB VRAM PCI card is not explicitly supported by NFS2 using the 
  2.14b beta driver from Diamond Multimedia. This was the most recent driver available at 
  the time of release; for a newer driver, call your local Diamond Multimedia customer 
  support office or check the Diamond Multimedia Web site at www.diamondmm.com (see your 
  video card manual for the customer support telephone number for your country).


STUTTERING OR SLUGGISH PERFORMANCE
==================================
In the event that the game stutters or performs sluggishly on your system, try the following 
suggestions for improving game performance. The benefits of each will vary upon your 
computer's processor type and speed, total memory, etc.

* Let Windows 95 manage virtual memory: Some systems may experience a brief pause during
  gameplay. This is due to Windows 95 virtual memory management. Ensure you allow Windows 95
  to manage virtual memory and that your hard disk has at least 30 MB free space for
  Windows 95 swap space. Windows 95 manages virtual memory by default. To enable automatic
  virtual memory management, click on the START button in the Windows 95 menu bar, select
  SETTINGS, then CONTROL PANEL. When the Control Panel window opens, double click on SYSTEM. 
  A System Properties control panel will open - select PERFORMANCE, then VIRTUAL MEMORY.
  Ensure that the option "Let Windows manage my virtual memory settings" is selected. Press
  OK, then press OK again. You will need to restart your system for the change to take effect.

* Avoid running other programs in the background: We strongly recommend that you shut down 
  all other Windows 95 applications before running Need For Speed II. Applications running 
  in the background use memory and processing power, and can cause gameplay to be sluggish 
  or stutter.

* Turn off racing music: From the main menu, select OPTIONS, then AUDIO, and set the racing 
  music level to the minimum setting - this turns off the racing music. All music is played 
  directly off of the game CD, so by turning off the racing music, the CD will not longer be 
  accessed to read music thus lightening the load on the CPU.

* Disable CD-ROM read-ahead caching: Click on the START button in the Windows 95 menu bar,
  select SETTINGS, and then CONTROL PANEL. Double click on the SYSTEM control panel. Select
  PERFORMANCE, FILE SYSTEM, and then CD-ROM. Change the "Optimize access pattern for"
  option to read "No read-ahead". This will disable CD-ROM read-ahead caching.  Press OK, 
  then press CLOSE. You will need to restart your system for the change to take effect.


SERIAL LINK PROBLEMS
====================
If you are experiencing difficulties establishing a serial game connection, check to ensure 
you are using a null-modem cable, and not a standard serial cable. Null modem cables are 
wired in a manner which allows two computers to talk to one another. If you discover that 
you are using a standard serial cable and not a null-modem cable, you can obtain an 
inexpensive "null modem adapter" from almost any electronics supply shop which you can 
connect to one end of the serial cable; this adapter serves the same function as a standard 
null-modem cable when used with a normal serial cable.


SOUND CARDS WITHOUT DIRECTX SUPPORT
===================================
If you are using a sound card, Need For Speed II requires that it be supported by DirectX 
drivers. If your sound card drivers do not have DirectX support, you may experience delayed 
sound, stuttering, or sound drop out.  In addition, you may experience some difficulties 
maneuvering in the menus with your joystick, if it is attached to the sound card's game 
port.  If this is the case, you can maneuver in the menus with your mouse or keyboard.  


WINDOWS NT
==========
Need For Speed II was written to operate under Windows 95 and does not specifically support 
Windows NT. If you are attempting to run the game under Windows NT and have questions 
related specifically to Windows NT, please contact Microsoft directly via the Customer 
Support contact methods supplied with your Windows NT documentation.


LEGAL
=====
NEED FOR SPEED is a trademark of Electronic Arts, Inc. WINDOWS, WINDOWS 95, 
WINDOWS NT, and DIRECTX are trademarks of Microsoft Corporation. This document is 
Copyright 1997 by Electronic Arts, Inc.

English README Revision 6
