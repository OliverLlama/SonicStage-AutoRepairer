# SSAR
Automates fixing ERROR **00004e2e** in Sony's SonicStage v4.0

The script copies all the ".dat" files from the "restorable" folder, and duplicates them into the OpenMG folder.
Afterwards it runs SonicStage.

The main purpose of the file is to act as a launcher for SonicStage.

IF you DON'T want to use it as a launcher, you can just remove the "&& cd ""C:\Program Files (x86)\Sony\SonicStage"" && start Omgjbox.exe" part of the script (Check if you didn't accidentally remove the ' aswell).

IF you have a custom install location, you will need to change the folder locations.

NOT tested on newer or older versions.
