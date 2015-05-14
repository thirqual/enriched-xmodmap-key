# enriched-xmodmap-key
An example of a xmodmap keymap with accents, greek, maths, and more.

To apply the script, 
1) first save your current xmodmap configuration with the command
xkbcomp $DISPLAY xkb.dump 
which will create a backup file for your current keyboard mapping
2) run the command 
xkbcomp xkb_custom $DISPLAY

To remove the script, run the command 
xkbcomp xkb.dump $DISPLAY

Current features:
- ctrl on caps lock
- compose on left ctrl
- 3rd level on right ctrl
- 5th level on right alt
- super on left win

- two layouts: qwerty and dvorak (switch from one to the other with your default system layout change shortcut, e.g. ctrl+alt+K in kde)
- greek letters and maths symbols on 5th level
- deadkeys for accents, extended latins characters and common symbols on 3rd level
- a few symbols on 3rd+5th level, and a lot of free room left.
