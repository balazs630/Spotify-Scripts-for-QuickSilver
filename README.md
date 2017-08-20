<img src="http://i.imgur.com/x56EUq7.png" width="80px" />
<h1>Spotify-scripts-for-QuickSilver</h1>
Spotify triggers written in AppleScript to control the playback functions under Mac OS X.


Quicksilver is a very handy tool to set custom keys or keyboard shortcuts to control your Applications. With these scripts you can preserve the default media control keys for iTunes and use different keys to control Spotify. Works too if Spotify is in the background and not the active application.

**Script functions:**
- Play/Pause
- Next Track
- Previous Track
- Volume Up
- Volume Down


**1.)** Install QuickSilver
    https://qsapp.com/index.php
    
**2.)** Add new triggers under Quicksilver.../Triggers... with the following properties:
  - Select an item: Browse one of the script file
  - Action: Run
  - Save
  
**3.)** Set up keyboard shortcut to trigger the action:
  - Shortcut: e.g. F15 key
  - Activate: On press

  ℹ️ For Volume Down and Volume up triggers I recommend using:
    Activate: On press, Repeat every: 0.1s
    This way the volume level continuously changes when you press and hold down the key
