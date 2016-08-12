# Spotify-scripts-for-QuickSilver
Spotify triggers written in AppleScript to control the playback functions under OS X.
Also works if Spotify is in the background and not the active application.

Functions:
- Play/Pause
- Next Track
- Previous Track
- Volume Down
- Volume Up

In order to set up:

1.) Install QuickSilver
    https://qsapp.com/index.php
    
2.) Add new triggers under Quicksilver.../Triggers... with the following properties:
  - Select an item: Browse one of the script file
  - Action: Run
  - Save
  
3.) Set up keyboard shortcut to trigger the action:
  - Shortcut: e.g. F15 key
  - Activate: On press

  For Volume Down and Volume up triggers I recommend using:
    Activate: On press, Repeat every: 0.1s
    This way the volume level continuously changes when you press and hold down the key
