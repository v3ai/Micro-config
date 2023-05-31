## This is my bindings file, there are many like it but this one is mine

- My bindings are always evolving 
- I wish I had more fingers
- to get the full experience bind Alt-W to toggle window max (keyboard settings)
- and bind Alt-, to close  window
- and Alt-t to open new terminal window
- and Alt-= to zoom in and Alt-- to zoom out in term
- and Alt-Spacebar to main menu
- and put this in your ~/.bashrc
```
bind '"\eh": backward-char'
bind '"\el": forward-char'
bind '"\en": beginning-of-line'
bind '"\em": end-of-line'
bind '"\ed": "\C-a\C-k"'
```
- and replace your ~/.config/micro/bindings.json file with mine
