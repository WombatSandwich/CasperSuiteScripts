CasperSuiteScripts
==================

A collection of scripts I have worked on to be used with the Casper Suite, and in some cases, which can be used with other Mac management tools.

###Current scripts
####**selectable-SoftwareUpdate.sh**<br>
- Requires the current beta release of cocoaDialog to be installed on the target Mac.
- Displays a checkbox dialog with available Software Updates to be installed.
- Provides feedback on installations as they run with a moving progress bar.

####**installLatestFlashPlayer-v1.sh**<br>
- Has built in Flash Player plug-in version checking against Adobe's website to determine if a newer release can be installed.
- Silently downloads the latest release (if needed) and installs the update, cleaning up the download at the end.
- Will not downgrade a client running a beta release of Flash Player.
- A flag can be set in the script to install or not install against a system that has no current version of FlashPlayer installed.
- Assuming Adobe does not change around their site, should continue to work when FlashPlayer is revved to version 14.x, etc.
- Can be used outside of the Casper Suite.

####**install_Latest_AdobeReader.sh**   (_New_)<br>
- Has built in Adobe Reader version checking against Adobe's website to determine if a newer release can be installed.
- Silently downloads the latest release (if needed) and installs the update, cleaning up the download at the end.
- Will not downgrade a client running a beta or newer release of Adobe Reader.
- A flag can be set in the script to install or not install against a system that has no current version of Adobe Reader installed.
- Assuming Adobe does not change around their site, should continue to work when Adobe Reader is revved to version 12.x, etc.
- Can be used outside of the Casper Suite.