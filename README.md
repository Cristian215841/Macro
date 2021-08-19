# tft-bluestacks

*requires a monitor 1080 pixels of vertical resolution, latest Java release, and SikuliX with Jython 2.7.1*

Download Jython from here:
https://repo1.maven.org/maven2/org/python/jython-standalone/2.7.1/jython-standalone-2.7.1.jar

Download Java from here:
https://www.java.com/en/download/win10.jsp

Download BlueStacks with Teamfight Tactics here:
https://www.bluestacks.com/apps/strategy/teamfight-tactics-on-pc.html

-Clone this repo to a location of your choice.


<b>BlueStacks Instance setup</b>

-Open "BlueStacks multi-instance manager" and locate your primary BlueStacks instance.

-Under Engine in instance settings, set cores to 2 (medium) under Performance and FPS to 20.

-Under Display, select "Landscape" and 960x540.


<b>BlueStacks Macro Importing</b>

-Open the primary instance and click the side menu icon (double arrow icon), followed by the macro recorder (clipboard with the play icon).

-Click the "import" icon (square with downwards arrow).

-Navigate to where you cloned this repo to and import everything in the "macros" folder.

-For shortcuts, type 1 for start_game, 3 for play_again, 7 for exit_modal, 6 for accept_game, and 8 for ff_game.

-Under each macro setting (gear icon), make sure "Don't show macro window when execution finishes" is checked.


<b>BlueStacks Instance creation and alignment</b>

-Set up 7 other instances cloned from the primary BlueStacks instance.

-Launch all instances (may cause brief loss of performance as emulators boot) and click "Arrange" in BlueStacks multi-instance manager.

-Given a theoretical layout where the following numbers represent the vertical and horizontal layout of the instances, 1 is a random smurf of your choice and 8 is your primary account:

1 2

3 4

5 6

7 8


-Take note of the names of the BlueStacks instances in positions 1-7. 

-Go to instance 1, click the hamburger menu, and select "Sync Operations". 

-Sync instances 1-7. Instance 8 is your account and runs different macro timings from your smurfs.

-Open all of the TFT apps. Apps may crash; simply re-open them. 


<b>In-game party setup</b>

-In instance 8, designate yourself as party leader and invite the other smurfs in instances 1-7 to your party.

-Accept the invitation on your smurfs. For maximum convenience, do this on the instance that your smurfs are synchronized to, as this saves you from needing to accept an invitation on 7 clients. 

-Open the folder where you cloned this repo to, and click on the shortcut. Make sure no windows, including the shortcut window, are obstructing the BlueStacks instances at any time.


-To quit, exit out of the command prompt or use the Task Manager to manually kill the Windows Command Prompt process.
