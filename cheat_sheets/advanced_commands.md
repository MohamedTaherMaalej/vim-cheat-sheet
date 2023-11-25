# Advanced Vim Commands Cheat Sheet

## Advanced Navigation

- **Ctrl + f**: Move forward one full screen.
- **Ctrl + b**: Move backward one full screen.
- **Ctrl + d**: Move forward half a screen.
- **Ctrl + u**: Move backward half a screen.
- **H**: Move to the top of the visible screen.
- **M**: Move to the middle of the visible screen.
- **L**: Move to the bottom of the visible screen.
- **%**: Move to the matching parenthesis, bracket, or brace.

## Marks and Macros

- **m{a-z}**: Set a mark at the cursor position (use a-z as the mark name).
- **`{a-z}**: Jump to the position of the specified mark.
- **:'a,'b copy a b**: Copy lines from mark a to mark b and paste them.
- **q{a-z}**: Record a macro into register a-z.
- **@{a-z}**: Execute the macro stored in register a-z.
- **@@**: Repeat the last executed macro.

## Split Windows

- **:split**: Split the current window horizontally.
- **:vsplit**: Split the current window vertically.
- **Ctrl + w, w**: Switch between windows.
- **Ctrl + w, h/j/k/l**: Move to the window to the left/down/up/right.
- **Ctrl + w, c**: Close the current window.
- **Ctrl + w, o**: Close all windows except the current one.

## Tabs

- **:tabnew**: Open a new tab.
- **:tabnext** or **gt**: Move to the next tab.
- **:tabprev** or **gT**: Move to the previous tab.
- **:tabclose**: Close the current tab.

## Registers

- **"{a-z}y{motion}**: Yank text to register {a-z}.
- **"{a-z}p**: Paste text from register {a-z}.
- **:registers**: Display the contents of all registers.

## Visual Mode

- **gv**: Reselect the last visual selection.
- **Ctrl + v**: Start visual block mode.
- **o**: Move to the other end of the visual block.

## Global Commands

- **:g/{pattern}/command**: Execute a command on lines matching a pattern.
- **:v/{pattern}/command**: Execute a command on lines not matching a pattern.

## Ex Commands

- **:s/{pattern}/{replacement}/g**: Substitute all occurrences of a pattern with a replacement.
- **:g/{pattern}/d**: Delete all lines matching a pattern.
- **:sort**: Sort lines alphabetically.

These advanced commands can significantly enhance your productivity in Vim. Experiment with them and incorporate them into your workflow for a more efficient text editing experience.

