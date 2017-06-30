VIM SHORTCUTS


Basics
------

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


Moves
-----

Description | Shortcuts
----------- | ---------
Move to left, bottom, up, right | `h,j,k,l`
Move to first, last line | `gg,G`


Combos
------
Just some samples that can be mixed \o/

Description | Shortcuts
----------- | ---------
Change inner word | `c i w`
Delete inner brackets | `d i (`
Yank inner quotes | `y i '`
Change to next comma | `c t ,`
Delete forward (to including) next dot | `d f .`


Panes
-----

Description | Shortcuts
----------- | ---------
Open specified file (current file by default) in a new horiz, vert pane | `:sp,:vs <filepath>`
Switch cursor to next, previous pane | `CTRL-w w,W`
Switch cursor to left, bottom, up, right pane | `CTRL-w h,j,k,l`     
Rotate all panes clockwise, anti-clockwise | `CTRL-w r,R`
Move current pane to left, bottom, up, right position | `CTRL-w H,J,K,L`
Swap current pane with next one | `CTRL-w x`
Resize current pane widthpane, height by # | `CTRL-w # >,<,+,-`
Change current pane width, height to # | `CTRL-w # \|,_`
Set equal sizes for all panes | `CTRL-w =`


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
