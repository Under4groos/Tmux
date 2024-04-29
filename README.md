# Install 
```
sudo apt-get install tmux
```
# Sessions
Kill all sessions
```
tmux kill-server
```


Kill session
```
tmux kill-session -t <name>
```




# Split frame
Horizontal
```
tmux split-window -hf
```
Verical
```
tmux split-window -vf
```
KeyBinds
```
ctrl + b + % - to make a vertical split.
ctrl + b + " - to make a Horizontal split.
ctrl + b +   - left arrow to move to the left pane.
ctrl + b + " - to make a Horizontal split.
```