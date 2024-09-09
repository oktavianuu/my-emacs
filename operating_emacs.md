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