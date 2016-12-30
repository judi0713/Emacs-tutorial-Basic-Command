Emacs tutorial Basic Command 

> Basic Mac GNU Emacs 25.1.1

### * SUMMARY

`C-v`　　Move forward one screenful
`M-v`　　Move backward one screenful
`C-l`　　Clear screen and redisplay all the text

### * BASIC CURSOR CONTROL

`C-p`　　Move to previous line
`C-n`　　Move to next line
`C-f`　　Move forward a character
`C-b`　　Move backward a character
`M-f`　　Move forward a word
`M-b`　　Move backward a word
`C-a`　　Move to beginning of line
`C-e`　　Move to end of line
`M-a`　　Move back to beginning of sentence
`M-e`　　Move forward to end of sentence

`M-<`　　Move to the beginning of the whole text
`M->`　　Move to the end of the whole text

### * IF EMACS STOPS RESPONDING

`C-u`　　Accept a numeric argument

### * DISABLED COMMANDS

`C-g`　　Stop a command which is taking too long to execute

### * WINDOWS
`C-x 1`　　One window

### * INSERTING AND DELETING

`<DEL>`　　Delete the character just before the cursor
`C-d`　　Delete the next character after the cursor

`M-<DEL>`　　Kill the word immediately before the cursor
`M-d`　　Kill the next word after the cursor
`C-k`　　Kill from the cursor position to end of line
`C-y`　　Reinserts the last killed text
`M-y`　　Back to the starting point
`M-k`　　Kill to the end of the current sentence

`C-<SPC>`　　Mark set
`C-w`　　Kill the text starting from the Mark set

### * UNDO

`C-/`　　Undo

### * FILES

`C-x C-f`　　Find a file
`C-x C-s`　　Save the file

### * BUFFERS

`C-x C-f`　　List buffers
`C-x b Filename <Return>`　　Back to File
`C-x s`　　Save some buffers

### * EXTENDING THE COMMAND SET

`C-x`　　Character eXtend.  Followed by one character.
`M-x`　　Named command eXtend.  Followed by a long name.

`C-x C-f`　　Find file
`C-x C-s`　　Save file
`C-x s`　　Save some buffers
`C-x C-b`　　List buffers
`C-x b`　　Switch buffer
`C-x C-c`　　Quit Emacs
`C-x 1`　　Delete all but one window
`C-x u`　　Undo

`M-x repl s<Return><Return>XXX<Return>`　　Replace String

### * AUTO SAVE

`M-x recover-file <Return>`　　Recover File

### * ECHO AREA

### * MODE LINE

`M-x Mode <Return>`　　Change Emacs Editing Mode

### * SEARCHING

`C-s`　　Forward search
`C-r`　　Reverse search 

### * MULTIPLE WINDOWS

`C-M-v`　　Scroll the next window
`C-x o`　　Move the cursor to the bottom window
　　
### * MULTIPLE FRAMES

`M-x make-frame <Return>`　　Set a new frame

### * RECURSIVE EDITING LEVELS

`M-x <ESC> <ESC> <ESC>`　　Get out recursive editing level

### * GETTING MORE HELP

`C-h c Command`　　Check command function
`C-h k Command`　　Get more information about a command
`C-h f`　　Describe a function
`C-h a`　　Command Apropos
`C-h i`　　Read included Manuals

### * MORE FEATURES

### * CONCLUSION
　　
`C-x C-c`　　Exit Emacs


