## LauncherJellyBean ##

The project contains the code for the Launcher app that ships with Android Jelly Bean (API 16).

Some minor changes were required from this source code to remove the use of private APIs. These changes have been marked by "// AOSP Change"


#### Known Issues: ####

1). Adding certain Widgets will cause a crash. For example, try adding the 3x3 Messaging Widget. 

2). Adding certain Widgets will not work. For example, try adding the 3x3 Gmail widget. This will appear to work, with the permission dialog displaying, and the Gmail app loading so you can select the account and folder to display. However, once that selection is made, the widget fails to appear, and the App Drawer comes back on screen. 