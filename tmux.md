TMUX
====
![TMUX](https://raw.githubusercontent.com/SergeBouchut/memo/master/tmux.png)


Basics
------

Description | Shortcuts
----------- | ---------
New session | `tmux`
List sessions | `tmux ls`
Attach session | `tmux -a`
Detach session | `CTRL-b d`

Windows (tabs)
--------------

Description | Shortcuts
----------- | ---------
Create window | `CTRL-b c`
List windows | `CTRL-b w`
Swith to next, previous window | `CTRL-b n,p`
Swith to window # | `CTRL-b #`
Kill current window | `CTRL-b &`


Panes (splits)
--------------

Description | Shortcuts
----------- | ---------
Vertical, horizontal pane | `CTRL-b %,"`
Switch to next pane | `CTRL-b o`
Change panes layout | `CTRL-b <space>`
Move current pane to the left, right | `CTRL-b {,}`
Kill current pane | `CTRL-b x`
Toggle pane zoom (full-screen mode) | `CTRL-b z`
Swap panes | `CTRL-b CTRL-o`
Resize pane | `CTRL-b CTRL-<arrow>`
