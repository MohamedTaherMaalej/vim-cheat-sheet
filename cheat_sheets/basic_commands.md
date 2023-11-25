# Basic Vim Commands Cheat Sheet

## Navigation

- **h, j, k, l**: Move left, down, up, or right respectively.
- **w**: Move forward to the beginning of the next word.
- **b**: Move backward to the beginning of the previous word.
- **e**: Move to the end of the current word.
- **0**: Move to the beginning of the line.
- **^**: Move to the first non-blank character of the line.
- **$**: Move to the end of the line.
- **gg**: Go to the first line of the document.
- **G**: Go to the last line of the document.
- **:n**: Move to the nth line.

## Inserting and Editing

- **i**: Enter insert mode before the cursor.
- **I**: Enter insert mode at the beginning of the line.
- **a**: Enter insert mode after the cursor.
- **A**: Enter insert mode at the end of the line.
- **o**: Open a new line below the current line.
- **O**: Open a new line above the current line.
- **x**: Delete the character under the cursor.
- **dd**: Delete the entire line.
- **yy**: Copy the entire line.
- **p**: Paste the copied or deleted text after the cursor.
- **u**: Undo the last change.
- **Ctrl + r**: Redo the last undone change.

## Exiting Vim

- **:w**: Save changes (write).
- **:q**: Quit Vim if no changes have been made.
- **:q!**: Quit Vim, discarding any changes.
- **:wq** or **:x**: Save changes and quit.
- **ZZ**: Save changes and quit.
- **ZQ**: Quit without saving changes.

## Searching

- **/pattern**: Search forward for a specific pattern.
- **?pattern**: Search backward for a specific pattern.
- **n**: Move to the next occurrence of the search pattern.
- **N**: Move to the previous occurrence of the search pattern.

## Copying, Cutting, and Pasting

- **v**: Start visual mode (character-wise).
- **V**: Start visual mode (line-wise).
- **y**: Yank (copy) the selected text.
- **d**: Delete (cut) the selected text.
- **p**: Paste the yanked or deleted text after the cursor.

## Miscellaneous

- **:set number**: Display line numbers.
- **:set nonumber**: Hide line numbers.
- **:help**: Open the help documentation.

Remember to practice these commands regularly to become more proficient with Vim. Happy editing!
