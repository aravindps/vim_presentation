# Vim session


## Install Vim

* `sudo apt-get install vim`

***

## Open & Close Vim terminal

* `vim filename.txt`
* q                   - quit
* w                   - write
* !                   - force
* Esc, C-c and C-[    - switch to normal mode

### Usage

* \<Esc\>:wq
* \<Esc\>:q
* \<Esc\>:q!

***

## Eclipse Vim Plugins
* Install vrapper
  `http://vrapper.sourceforge.net/update-site/stable`
* Install relative number
 ` http://matf.github.io/relativenumberruler/updatesite/`

***

## Modal Editing

* `:help vim-modes`
* Insert Mode  - editing the file
* Visual Mode  - highlight portions of the file to manipulate at once
* Command Mode - :commands. Executes a command and comes back to normal mode
* Ex Mode      - :commands. Stays in command mode
* Replace Mode - replace characters under the cursor
* Normal Mode  - navigate through the file

***

### Insert Mode

* Type content

***

### Visual Mode

* v        - visual mode from current cursor position
* Shift-v  - line visual mode
* Ctrl-v   - block visual mode

***

### Command mode

* Config and advanced commands
* set number         - enable line number
* set relativenumber - enable relative number

***

### Ex mode

* Enters all time command mode

***

### Replace Mode

* r\<replace-char\>      - replace a char.
* R\<replace-chars\>     - replace more than one character
* \<Esc\>                - move to normal mode

***

### Normal Mode
![Normal mode](https://raw.githubusercontent.com/aravindps/vim_presentation/master/vim_shortcuts.png)

***

### Normal Mode (continued)

* nG     - move to nth line number
* 1G     - move to 1st line
* GG     - move to last line

* i      - insert under the cursor
* a      - append after the cursor
* I      - insert at the *start* of the line
* A      - append at the *end* of the line
* ~      - toggle case

* o      - add new line at the *bottom* and enter insert mode
* O      - add new line at the *top* and enter insert mode

* /      - search *forward*. /searchpattern
* ?      - search *backward*. /searchpattern

* ?      - search the word under the cursor *forward*
* \#     - search the word under the cursor *backward*

* n      - move in search direction
* N      - move in reverse direction

* x      - delete/cut a char *after* the cursor [Del]
* X      - delete/cut a char *before* the cursor [Backspace]
* y      - yank
* yy     - yank a line
* dd     - delete/cut a line
* p      - paste

***

### Text Object

* w - words
* s - sentences
* p - paragraphs
* t - tags

***

### Motions

* a - all
* i - in
* t - 'til forward
* T - 'til backward
* f - find forward
* F - find backward

***

### Commands

* d - delete(also cut)
* c - change(delete, then plate in insert mode)
* y - yank(copy)
* v - visuallly select

***

### Usage

**{command}{count}{motion}{text-object}**

* d2w
* ci)
* yi"

***

### Repeat Operator

* ;(semi-colon) and ,(comma) operator - repeat motion forward and backword
* .(dot) operator                     - repeat last edit

***

### Macros

* q\<register\>  - record a macro in <register>
* q              - stop recoding a macro
* @\<register\>  - run macro

***

## More vim

* `vimtutor`
* [http://derekwyatt.org/vim/tutorials/index.html](Video for Novice, Intermediate to Advanced vimmers)
* [http://vim-adventures.com/](Vim Adventure)
* [http://www.vimsnake.com/](Vim snake)
* [https://www.youtube.com/watch?v=5r6yzFEXajQ](Vim + tmux)
* [http://www.fprintf.net/vimCheatSheet.html](vim cheatsheet)

***

-># Thanks<-
