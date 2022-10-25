# American McGee's Alice fix for Windows 10 for Origin  

# NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not affraid to take the risk of learning some new stuff in the process.

# Reviving another classic game: 
# Here is how to get that American McGee's Alice Classic from 2000 working with the official version of Alice:Madness Returns 2011 from Origin and Steam

1. You need to buy the copy of the original 2011 game Alice: Madness Returns from Origin or Redeem your Steam Key in the Origin client

2. Download and install Alice:Madness Returns from Origin

3. Run the game at least once

4. Download Alice 1 from this link: 
* https://drive.google.com/drive/folders/1P54riPxUKFMFYR8ifhoK30xx89nSzfRK?usp=sharing
Or Nextcloud:
* https://ann.nl.tab.digital/s/Twoj2T7F2GgzHJc

5. Go to C:\Users\User\Documents\My Games\Alice Madness Returns\AliceGame\Config

6. Look for AliceEngine.ini file

7. Edit it with notepad:

* Change this one line GIsSpecialPCEdition=FALSE to GIsSpecialPCEdition=TRUE

8. Copy the Alice 1 folder into C:\Program Files (x86)\Origin Games\Alice Madness Returns\Game

9. Launch Alice:Madness Returns again

10. Select option to play American McGee's Alice

# For Steam versions:
1. Download and install Alice:Madness Returns from Steam

3. Run the game at least once

4. Download Alice 1 from this link: 
* https://drive.google.com/drive/folders/1P54riPxUKFMFYR8ifhoK30xx89nSzfRK?usp=sharing
Or Nextcloud
* https://ann.nl.tab.digital/s/Twoj2T7F2GgzHJc

5. Copy the Alice 1 folder into C:\Program Files (x86)\Steam\steamapps\common\Alice Madness Returns

6. Go to C:\Users\User\Documents\My Games\Alice Madness Returns\AliceGame\Config

7. Look for AliceEngine.ini file

8. Edit it with notepad,replace the entire [AliceGame.AliceGameEngine] seection with these lines:

[AliceGame.AliceGameEngine]
Alice1Path=..\..\Alice1\bin
GIsSpecialPCEdition=TRUE

9. Launch Alice:Madness Returns again

10. Select option to play American McGee's Alice

#(Optional) 60 FPS Fix for Alice Madness Returns:
1. Go to C:\Program Files (x86)\Steam\steamapps\common\Alice Madness Returns\AliceGame\Config
2. Find the DefaultEngine file 
3. Edit with notepad
4. Find the following values
MinSmoothedFrameRate=22
MaxSmoothedFrameRate=31
5. Change one of these values to: 
MinSmoothedFrameRate=22
MaxSmoothedFrameRate=60


#Additional steps if something is broken,game does not work correctly,etc:

1. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support


2. Check on AMD/NVIDIA GPU’s if the driver is up to date,if not reinstall using DDU
(no need for safe mode,just restart normally and install the latest driver version):
https://www.guru3d.com/files-details/display-driver-uninstaller-download.html

3. Follow the guide,do a clean/fresh reinstall(delete all folders in Steam with the Alice: Madness Returns game and make sure that the game is located in C:\Program Files(x86) directory.

4. On Intel+NVIDIA (laptops) make sure that Alice:Madness Returns game is using NVIDIA as main GPU in NVIDIA Control Panel. 


# Cheers, silentgamepls:
