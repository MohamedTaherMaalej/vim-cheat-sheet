# Vim Search and Replace Cheat Sheet

## Searching

- **/pattern**: Search forward for a specific pattern.
- **?pattern**: Search backward for a specific pattern.
- **n**: Move to the next occurrence of the search pattern.
- **N**: Move to the previous occurrence of the search pattern.
- *** or #**: Search for the word under the cursor (forward/backward).

## Search and Replace

### Basic Search and Replace

- **:%s/{old}/{new}/g**: Replace all occurrences of `{old}` with `{new}` in the entire file.
- **:s/{old}/{new}/g**: Replace all occurrences of `{old}` with `{new}` in the current line.
- **:n, m s/{old}/{new}/g**: Replace all occurrences of `{old}` with `{new}` in lines `n` through `m`.

### Confirming Replacements

- **:%s/{old}/{new}/gc**: Replace all occurrences with confirmation.
- **:s/{old}/{new}/gc**: Replace in the current line with confirmation.
- **:n, m s/{old}/{new}/gc**: Replace in lines `n` through `m` with confirmation.

### Using Regular Expressions

- **:%s/{pattern}/{replacement}/g**: Replace using regular expressions.
- **:s/{pattern}/{replacement}/g**: Replace in the current line using regular expressions.
- **:n, m s/{pattern}/{replacement}/g**: Replace in lines `n` through `m` using regular expressions.

### Modifiers

- **:%s/{pattern}/{replacement}/gi**: Case-insensitive global replace.
- **:%s/{pattern}/{replacement}/gI**: Case-sensitive global replace.
- **:%s/{pattern}/{replacement}/n**: Report the number of occurrences replaced.

### Backreferences

- **:%s/\(\d\)\(\w\)/\2\1/g**: Swap the first digit and the first word character in each line.

### Saving Changes

- **:w**: Save changes.
- **:wq** or **:x**: Save changes and quit.
- **ZZ**: Save changes and quit.

Search and replace are powerful features in Vim, and understanding these commands will greatly enhance your editing capabilities. Experiment with different options to suit your needs.
