---
tags: 
Links:
  - "[[My Linux]]"
---
- - -
# Vim Cheat Sheet

## Navigation

- `h` : Move left
- `j` : Move down
- `k` : Move up
- `l` : Move right
- `w` : Move to the start of the next word
- `b` : Move to the start of the previous word
- `e` : Move to the end of the word
- `0` : Move to the beginning of the line
- `^` : Move to the first non-blank character of the line
- `$` : Move to the end of the line
- `gg` : Move to the first line of the file
- `G` : Move to the last line of the file
- `:{n}` : Move to line number `n`

## Editing

- `i` : Enter insert mode before the cursor
- `I` : Enter insert mode at the beginning of the line
- `a` : Enter insert mode after the cursor
- `A` : Enter insert mode at the end of the line
- `o` : Open a new line below the current line and enter insert mode
- `O` : Open a new line above the current line and enter insert mode
- `x` : Delete the character under the cursor
- `dd` : Delete the current line
- `d{motion}` : Delete text according to the motion (e.g., `dw` deletes a word)
- `y{motion}` : Yank (copy) text according to the motion
- `p` : Paste the yanked or deleted text after the cursor
- `P` : Paste the yanked or deleted text before the cursor
- `u` : Undo the last change
- `Ctrl + r` : Redo the undone changes
- `.` : Repeat the last command

## Visual Mode

- `v` : Enter visual mode (character selection)
- `V` : Enter visual line mode (line selection)
- `Ctrl + v` : Enter visual block mode (block selection)
- `y` : Yank selected text
- `d` : Delete selected text
- `c` : Change selected text

## Search and Replace

- `/pattern` : Search for `pattern`
- `?pattern` : Search backward for `pattern`
- `n` : Repeat search forward
- `N` : Repeat search backward
- `:%s/old/new/g` : Replace all occurrences of `old` with `new` in the file
- `:s/old/new/g` : Replace all occurrences in the current line

## File Operations

- `:w` : Save the file
- `:q` : Quit Vim
- `:wq` : Save and quit
- `:q!` : Quit without saving
- `:e filename` : Open `filename`
- `:bnext` : Switch to the next buffer
- `:bprev` : Switch to the previous buffer
- `:buffers` : List all buffers
- `:bd` : Delete (close) the current buffer

## Miscellaneous

- `:set number` :​⬤








- - -
`=this.file.ctime`