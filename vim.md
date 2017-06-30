VIM SHORTCUTS


Edit
----

Description | Shortcuts
----------- | ---------
Insert, insert at the beginning | `i,I`
Append, append at the end | `a,A`
Replace, replace until the ESC | `r, R`
Change (remove + insert), to the end, from the beginning | `c,C,cc`
Delete (cut), to the end, from the beginning | `d,D,dd`
Yank (copy), to the end, from the beginning | `y,Y,yy`
Paste, paste before | `p,P`
Insert new line, insert new line before | `o,O`


Combos
------

Description | Shortcuts
----------- | ---------
Change, delete inner word, brackets | `c,d i w,(`


Panes
-----

Description | Shortcuts
----------- | ---------
Open a file in a new horizontal, vertical pane | `:sp,:vs`
Open the current file in a new horizontal pane | `^w n`
Open an empty new horizontal pane | `^w s`
Switch cursor to next, previous pane | `^w w,W`
Switch cursor to left, bottom, up, right pane | `^w h,j,k,l`     
Rotate all panes clockwise, anti-clockwise | `^w r,R`
Move current pane to left, bottom, up, right position | `^w H,J,K,L`
Swap current pane with next one | `^w x`
Resize current pane widthpane, height by # | `^w # >,<,+,-`
Change current pane width, height to # | `^w # \|,_`
Set equal sizes for all panes | `^w =`


Marks
-----

Description | Shortcuts
----------- | ---------
Create a new mark # | `m #`
Switch to mark # | `' #`
List all marks | `:marks`


Folds
-----

Description | Shortcuts
----------- | ---------
Open, close current fold | `z o,c`
Open, close all folds | `z M,R`
Set fold method based on identation (for XML files) | `:set fdm=indent`
