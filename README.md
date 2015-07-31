# LaunchBarActionsFromDave

Launch Bar Actions What I have Made

These are constructed with the LaunchBar Action Editor (⌥⌘E). After installing any (by double-clicking them), you should have them appear in the index automatically.

Some actions may need customising to your local system - check below for their requirements.

## Say In Korean

*Say In Korean* uses OS X's text to speech engine to vocalise any text passed to it - ideally, Korean Hangeul. You will need to install the Yuna voice - you can do this in Launchbar by searching for "DICTSPEE" to pull up the Dictation and Speech Preferences pane, moving to the "Text to Speech" tab, clicking the "System Voice" menu then picking "Customize...", then activating "Yuna". This will then download the voice files.

This does not change your system default voice settings when used.

You can send text to it with instant send, or press space and enter text in LaunchBar.

## Slogger

*Slogger* is an absolutely minimal (just an icon, really) action to launch Slogger, if you have it installed.

It expects you to have a `.bin` folder in `~` and there to be a bash script there which does the *actual* work of launching Slogger. If you need to change this, open up the Sloggger action in LaunchBar's Action Editor (⌥⌘E) and edit the script - you could launch Slogger directly, depending on how you have installed your local copy.

Slogger is by Brett Terpstra and [available on GitHub](http://ttscoff.github.io/Slogger/).
