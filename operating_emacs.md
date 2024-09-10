## Starting Emacs
* emacs -nw     : run emacs in terminal/ command line
* emacs -q      : do not load init file, pure emacs
* emacs -Q      : Does not load the site-wide startup file6 , your init file, nor X resources


## Emacs Interface


## Emacs Keys
C-d     : delete characters next to it
C-M-d   : do similar thing
C-x C-f : find file

## Caps Lock as Control
--later--

## M-x: Execute Extended Command
--later--

## M-S-x: Execute Extended Command for Buffer
--later--

## Info Manual
M-x info    : emacs info manual
C-h i       : same
#### Navigate through info manual
[ and ]     : previous and next node
l and r     : Go back/ forward in history
n and p     : previous or next sibling node
u           : goes up one level to a parent node
SPC         : scroll one screen at a time
TAB         : Cycles through cross-references and links
RET         : opens the active link
q           : closes the info browser

#### C-x C-c
What to do after exiting emacs? There are several options as follows:
Y or yes    : Save the files
N or DEL    : skip current buffer
q or RET    : aborts the saves, continues with exit
C-g         : aborts save and the exit
!           : save all remaining buffer
d           : Diff the file on the file system with the one in the buffer

#### C-x b: Switch Buffer
C-x b       : go to the last buffer we visited
C-x C-s     : writing buffer to files
C-x C-b     : display list of buffer running in emacs

#### C-x k: Kill Buffer
Killing a buffer in Emacs means closing it. You don’t have to kill buffers you don’t use. It’s perfectly normal to let them sit in the background until you need them again. Normally, se- rious Emacs users have hundreds or even thousands of open buffers at a time.

#### ESC ESC ESC: keyboard escape
The click your heels three times key. If you’re stuck somewhere or want to “go back to normal” — then pressing ESC ESC ESC will (probably) solve your problems.
All windows are deleted (meaning they’re hidden from view), prompts are exited out of, special buffers are hidden, prefix arguments are cancelled, and recursive editing levels are unwound.