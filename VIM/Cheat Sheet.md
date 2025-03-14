# Vim Cheat Sheet

## ✨ 1. Basic Controls
- `i` → Enter **Insert** mode
- `Esc` → Exit **Insert** mode
- `:w` → Save file
- `:q` → Quit Vim
- `:wq` or `ZZ` → Save and quit
- `:q!` → Quit without saving

---

## ✨ 2. Moving Around
- `h` → Move **left**
- `l` → Move **right**
- `j` → Move **down**
- `k` → Move **up**
- `w` → Move to the **next word**
- `b` → Move to the **previous word**
- `0` → Move to the **beginning of the line**
- `^` → Move to the **first non-whitespace character** in line
- `$` → Move to the **end of the line**
- `gg` → Move to the **beginning of the file**
- `G` → Move to the **end of the file**
- `Ctrl + d` → Move **half a page down**
- `Ctrl + u` → Move **half a page up**
- `Ctrl + f` → Move **one page down**
- `Ctrl + b` → Move **one page up**

---

## ✨ 3. Editing Text
- `x` → Delete a character
- `dw` → Delete a word
- `dd` → Delete **entire line**
- `D` → Delete from current position to end of line
- `yy` → Copy (Yank) the **entire line**
- `p` → Paste after cursor
- `P` → Paste before cursor
- `u` → Undo last change
- `Ctrl + r` → Redo undone change
- `.` → Repeat last edit

---

## ✨ 4. Searching and Replacing
Search:
- `/text` → Search forward for `text`
- `?text` → Search backward for `text`
- `n` → Jump to **next** search result
- `N` → Jump to **previous** search result

Replace:
```vim
:%s/old/new/g
```
Replace all occurrences of `old` with `new` in the file.

To confirm before replacing:
```vim
:%s/old/new/gc
```

---

## ✨ 5. Visual Mode (Selecting Text)
- `v` → Enter **Visual Mode** (select characters)
- `V` → Select **entire lines**
- `Ctrl + v` → Enter **Block Mode**
- `y` → Yank (copy) selected text
- `d` → Delete selected text

---

## ✨ 6. Working with Multiple Files & Tabs
- `:e filename` → Open a file
- `:tabs` → List open tabs
- `:tabnew filename` → Open file in a new tab
- `gt` → Move to the next tab
- `gT` → Move to the previous tab

---

## ✨ 7. Macros (Automation in Vim)
1. `qa` → Start recording a macro in register `a`
2. Perform actions
3. `q` → Stop recording
4. `@a` → Play macro
5. `@@` → Repeat last macro

---

## ✨ 8. Useful Plugins for Vim
If you're using Vim as your main editor, consider these plugins:
- `vim-plug` → Plugin manager
- `NERDTree` → File explorer
- `vim-airline` → Status bar enhancement
- `fzf.vim` → Fuzzy file search
- `coc.nvim` → Autocomplete & LSP support

---

## ✨ 9. Extra Resources
To learn more about Vim, check out:
- `:help` inside Vim
- `vimtutor` for an interactive Vim tutorial

Happy Vimming! 🚀

