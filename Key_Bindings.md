# Shortcuts

## Cursor moving

    * `CTRL+A` -> Move the cursor to the start of the line.
    * `CTRL+E` -> Move the cursor to the end of the line.
    * `CTRL + Right Arrow` or `ALT+F`  -> Move the cursor back one word.
    * `CTRL + Left Arrow` or `ALT+B` -> Move the cursor forward one word.

## Text edition

    * `CTRL+L` -> Clear the screen.
    * `ALT+U` -> Capitalize the word after the cursor.
    * `ALT+L` -> Lower the word after the cursor.
    
## Process control

    * `CTRL+C` -> Interrupt the current process.
    * `CTRL+Z` -> Suspend the current process. Use the commands `fg` to start it again in foreground or `bg` to start it again in background.
    * `CTRL+D` -> Exit bash shell (same as `exit` command)
    * `CTRL+S` -> Pause all command output to the screen.
    * `CTRL+Q` -> Resume output to screen (after *CTRL+S*).

# Bash Bang(!) commands

    * `!!` -> Equal to the last command executed.
    * `![n]` -> Repeat the nth command from your history `!-1` is the same as `!!`
