VIM
===


Basics
------

Description | Shortcuts
----------- | ---------
Insert, insert at the beginning | `i,I`
Append, append at the end | `a,A`
Replace, replace until the ESC | `r, R`
Change (remove + insert), change to the end | `c,C`
Delete (cut), delete to the end | `d,D`
Yank (copy), yank to the end | `y,Y`
Paste, paste before | `p,P`
Insert new line, insert new line before | `o,O`
Auto indent, increase indent, decrease indent | `=,<,>`
Change shift (indent) width | `:set sw=2`
Toggle, lower, upper case,  | `~,gu,gU`
Change, delete, yank, indent all the current line | `cc,dd,yy,==,<<,>>`
Undo, redo | `u,CTRL-r`


Moves
-----

Description | Shortcuts
----------- | ---------
Move one step to left, bottom, up, right | `h,j,k,l`
Move to first, last line | `gg,G`
Move to next, previous word | `w,b`
Move to next, previous search result | `n,N`
Move down, up | `CTRL- d,u`
Move to line # | `# G`


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
Indent all the file | `gg = G`


Panes
-----

Description | Shortcuts
----------- | ---------
Open file (current file by default) in a new horiz, vert pane | `:sp,:vs <filepath>`
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
Go further: http://vim.wikia.com/wiki/Folding?useskin=monobook

Description | Shortcuts
----------- | ---------
Open, close current fold | `z o,c`
Open, close all folds | `z M,R`
Set fold method based on identation (for XML files) | `:set fdm=indent`
