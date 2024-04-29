# For check
I am writing this instruction for myself. There is no need to write to me that everything is on the Internet.

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
KeyBinds
```
ctrl + b, x  - kill panel
```


# Split frame
Horizontal
```
tmux split-window -hf
```
![enter image description here](https://github.com/Under4groos/Tmux/blob/master/Images/Horizontal_split.png?raw=true)

Verical
```
tmux split-window -vf
```
![enter image description here](https://github.com/Under4groos/Tmux/blob/master/Images/Horizontal_split.png?raw=true)

KeyBinds
```
ctrl + b + % - to make a vertical split.
ctrl + b + " - to make a Horizontal split.
ctrl + b +   - left arrow to move to the left pane.
ctrl + b + " - to make a Horizontal split.
```