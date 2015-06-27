# AppleScript JXA TextMate Bundle

This is a bundle I came up with so I could write JXA for my Applescripts.

It's an Frankenstein-like mix of the original TextMate JavaScript bundle and the AppleScript Bundle.

To install, put it in your ~/Library/Application Support/Avian/ folder and double-click it.

# Using

Any .jxa file you create can be run with Command-R. It wil use OSAScript to run.

## Interesting Snippets

Some of the TextMate snippets you'll find are:

* **New JXA File** - Create a new JXA file. This will run with %R and log to the TextMate run window output. It will also run from the command-line. It looks like this:
* **Display Dialog** - Display a dialog box
* **Choose from List** - Choose an item from a list
* **Choose File** - Choose a file.
* **Display Prompt** - Prompts for input


Note: Remember it the script has to live on the directory for the appropriate app - ~/Library/Scripts/TargetApp to actually display dialogs


Many thanks to the magnificent [JXA Cookbook](https://github.com/dtinth/JXA-Cookbook), which these snippets are taken from.
