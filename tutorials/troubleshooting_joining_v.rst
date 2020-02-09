#############################
Troubleshooting Joining Owl V
#############################
.. _bug tracker: https://bugs.owlgaming.net/
.. _UAT Contact: https://forums.owlgaming.net/forms/10-upper-administration-contact-ooc/
.. _Support Center: https://owlgaming.net/support/
.. _Owl Launcher: http://files.owlgaming.net/OwlLauncher.exe
.. _tutorial here: https://wiki.rage.mp/index.php?title=Getting_Started_with_Client
.. _RAGE Troubleshooting: https://rage.mp/forums/topic/1816-client-troubleshooting-tips-fixes/

.. note::
    If this troubleshooting guide does not help, please seek further assistance on our Discord and Forums. If a solution for joining our GTA V server is not on here and has helped you, please inform the staff of OwlGaming so we may keep this as up to date as possible!

**********
In General
**********
Check to ensure that you have allowed RageMP access through your firewall and antivirus. These may be blocking your connection or the client from functioning properly, preventing you from joining Owl V. Additionally, verify that you have installed RageMP properly and meet their requirements by viewing their `tutorial here`_.
RAGE Multiplayer does not support pirated copies of Grand Theft Auto V, therefore in order to play, you must ensure you have a legitimate copy of the game. 

**************
Owl V Launcher
**************
The first thing we recommend for those having trouble connecting to our Owl V server is to use our `Owl Launcher`_ that will automatically verify your RageMP files are set up properly. Some users have reported receiving a "Windows SmartScreen" error when runnig the launcher. This may be ignored. Click "More Info" and then "Run Anyway" to continue running the launcher.

********************
Windows 7 / Keybinds
********************
At this time, RageMP does not support Windows 7 fully. As a result, you may be able to connect to the server but critical components may not work like keybinds aside from default controls. These keybinds end up being crucial to custom controls our server uses. To remedy this, we recommend that you upgrade to Windows 10.

********************
Enable Clientside CS
********************
.. note::
    Please ensure file name extensions is turned on. If they are not, you might accidentally name the file with an additional ".txt" which will cause an error.

Ensure you have added a file called **"enable-clientside-cs.txt"** to your RageMP installation. Do not make the file extention in all caps like **".TXT"** and ensure it's a text file, not another filetype named **".txt"** or a text file with an extra ".txt" added onto the

.. figure:: https://i.imgur.com/ftTaz3N.png

    With file extensions turned **ON** your file should look like this.

.. figure:: https://i.imgur.com/DlAVWbH.png

    To ensure file name extensions is turned on, this is where it is in your folder view options.


**************************************
Spawned As A Dog / Storage .blob Error
**************************************
If you spawned as a dog and or get a popup error similar to **"Data Storage Error #4"** or **"Data Storage Error #2"** with **"undefined:0"**, this may be fixed by navigating to your **"blob_storage"** folder located inside your Rage install folder and deleting the contents inside. 
Another cause for spawning as a dog is due to your enable-clientside-cs txt file not being set up properly in your RAGE directory.

.. figure:: https://i.imgur.com/gPUd2xY.png

    An example of the type of error received.

***********
.NET Errors
***********
Some users are unable to launch their game through Rage in general. This is because of a .NET "FATAL ERROR".

.. figure:: https://i.imgur.com/8T2dlsD.png

    An example of the type of error received.

To fix this issue you'll want to update your .NET Framework packages from your Windows 10 Updater, not from a download on the Microsoft website to ensure you are using the appropriate version. If this problem persists, ensure that you do not have any compatibility mode turned on for your RageMP or GTA V executables. Turning on compatibility mode will make it so Windows 10 .NET Framework packages are not used and thus break the launching of the game.


*********************
General RageMP Issues
*********************
When having issues with RageMP launching or allowing you to connect to a server or launch the game in general, it is always a good idea to ensure that you have a version of GTA 5 that RageMP supports and you have all of the files necessary for the game to run. Steam allows you to verify the integrity of your game files. This is highly recommended when experiencing these issues. You should also run your GTA 5 singleplayer at least once after a fresh install.
If you are still having issues with RageMP itself, click here for their `RAGE Troubleshooting`_ page.







