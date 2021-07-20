# Unofficial Xenia Updater
Small program made to manage Xenia emulator and its versions.

# Releases

* [**Stable**](https://github.com/Chopper1337/XeniaUpdater/raw/main/bin/Release/XeniaUpdater.exe)
* [Debug](https://github.com/Chopper1337/XeniaUpdater/raw/main/bin/Debug/XeniaUpdater.exe)

# Features

* Compatible with master branch and both canary branches of Xenia.
* Downloads and extracts latest builds of Xenia in one click
* Creates a backup of the last downloaded version of Xenia

# Info for anyone who plans to modify this code

To add different builds of Xenia, add two new buttons, one for updating and the other for starting that build. In the click event for those buttons, use the UpdateXenia and StartXenia methods to pass required parameters to update and start respectively.

# Note for "Debug" release

There is no guarantee of stability with the debug release.

Debug release will have the latest features.

If you run into any issues, message me on Discord **Chopper#4291**.
Try provide as much info as possible, screenshot of when the issue occurred and a screenshot of the directory the updater was in and so on.

A log file should be generated with the last error the program had, provide this if possible.

Thanks :)
