# How to Navigate TempleOS

## Controls & Shortcuts

### Mouse Controls
`Right Click`: Right-Click Menu
`Left Click`: Edit (view)
`Double Left`: Save & Exit
`Double Right`: Abort & Exit
`Top of Scrn`: Pull-down menu (use `<WINDOWS KEY>` instead.)

### Keyboard Controls
If you ever forget what your shortcuts are, simply hold one of the sortcut
keys (CTRL, ALT, +SHIFT) or a combination of for more than one second to see
a window that displays available shortcuts while the AutoComplete window is
active.

- `<DIRECTIONAL-ARROWS>`: Move the cursor.

- `<ALT-a>`: Opens AutoComplete
- `<ALT-SHIFT-a>`: Closes AutoComplete

- `<SPACE>`: Left click
- `<ENTER>`: Right click
- `<F1>`: Open Help page and index
- `<CTRL-m>`: Open your Personal Menu
- `<ESC>`: Save & Exit, accept dialog.
- `<SHIFT-ESC>`: Abort & Exit
- `<WINDOWS KEY>`: Pull-Down Menu (Navigate with arrows while holding)

- `<CTRL-ALT-t>`: New terminal window.
- `<CTRL-b>`: toggles border window
- `<ALT-m>`: Maximizes a window
- `<ALT-v>`: Vertically tiles windows.
- `<ALT-h>`: Horizontally tiles windows.
- `<CTRL-ALT-n>`: Switches to the next window.
- `<CTRL-ALT-x>`: Kills a window.

Customize the ALT keys in `~/HomeKeyPlugIns.HC`.

### Mouse+Keyboard Controls
`Ctrl-LeftDrag`: Grab-Scroll Window
`Ctrl-Right`: Recenter view after scrolling
`<CTRL-ALT-z>`: Zoom screen on mouse
`<CTRL-ALT-Z>`: Unzoom screen on mouse

## Functions

### Dir
Lists the contents of a directory.
```
> Dir("/your/path"); // Specified directory
> Dir(); // Present directory.
> Dir; // Parens are not needed with no args.
```
Parens are not required if there are no arguments.

### Cd
Change your current working directory.
```
> Cd; // Goes to ~
> Cd("mydir/myotherdir"); // A relative path.
> Cd("C:/Doc"); // An absolute path with drive.
```
