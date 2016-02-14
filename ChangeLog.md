
---


# Contents #



---


# 0.4.2 #

## Linux ##

  * Compensated for a change to Fcron's output format
  * Prevented the column header text from being absent
  * Tidied up the gathering of user environment variables
  * Handled case where list character isn't in UTF set


---


# 0.4.1 #

## Linux ##

  * Better handling if Fcron config file can't be read
  * Updated the 'clean' Makefile function for Python v3


---


# 0.4.0 #

## Linux ##

  * The Fcrontabs of other users can now be edited
  * External options can be configured via the GUI
  * A warning message is shown if spool dir is private
  * Now ignoring any unwanted status lines on load
  * Improved the error detection ability when saving
  * Removed enclosing quotes from script pathnames
  * Error messages force the main dialog to be visible
  * Forced the Makefile to build in serial mode
  * Makefile checks dir/file permissions were set
  * Changed the order of execution for the startup code
  * Improved how messages are handled and printed
  * Downsized most icons to 16x16 to reduce bloat
  * Removed support for the old KDE v3 environment
  * Made several minor changes to the code structure


---


# 0.3.0 #

## Linux ##

  * Upgraded the source code for Python v3 support
  * Can now select and manipulate multiple entries
  * Text can be searched for, highlighted if found
  * Added MRU lists to text fields for convenience
  * Contents of MRU lists can be cleared if desired
  * The layout of the context menu has been improved
  * Running errors are shown for the current user
  * Enhanced the information notification techniques
  * The dialog box sizes are now fully adjustable
  * Dialog widgets are now auto-spaced for clarity
  * The main form size is remembered between sessions
  * The Makefile enforces building before installing
  * Made some structural improvements to the Makefile
  * Added basic build and installation instructions
  * Deprecated distribution-specific build scripts
  * Improved the clarity of the licensing conditions
  * Added a link to each license in the 'Help' menu
  * Improvements were made to the update checking code
  * Made several minor changes to the code structure


---


# 0.2.0 #

## Linux ##

  * Run commands: via the right-click context menu
  * Daemon status: is now displayed on a push-button
  * Title-bar: now displays the current user's name
  * Time limit: removed from loading/saving processes
  * Line parsing: for freq sections with '`-`' or '`~`'
  * Save aborting: now gives user correct feedback
  * Temp Fcrontabs: now removed after loading/saving
  * Code structure: several minor changes


---


# 0.1.5 #

## Linux ##

  * Disabled hiding: to hide disabled lines and spans
  * Line folding: to show/hide all spans in tandem
  * Cloning action: for non-empty lines and spans
  * Clearing action: for non-empty lines and spans
  * Delete all: to remove all lines at once
  * Fcrontab removal: when saving empty Fcrontabs
  * Editing restrictions: increased for correctness
  * Line parsing: now supports those starting with a '`*`'
  * Code structure: several minor changes


---


# 0.1.0 #

## Linux ##

  * View and edit user's and system Fcrontab
  * In-place editing of tabulated Fcrontab lines
  * Check-boxes to enable or disable each line
  * Inserting, appending, spanning and deleting entries
  * Drag-and-drop moving of entries to new locations
  * The modified Fcrontab is installed when saving
  * A backup of the original is made after loading
  * Ability to revert, losing all recent changes
  * Right-click context menu with editing actions
  * Combo-box to switch between user and system modes
  * Different coloured column texts and line backgrounds
  * Prompt to save before loading or quitting
  * Resolution-relative and resizable main window
  * Dialog widgets: are now auto-spaced for clarity
  * Tree view to allow spanning multiple lines
  * All general features from Q7Z and Quamachi