# For check
I am writing this instruction for myself. There is no need to write to me that everything is on the Internet.

# Install / Установка Tmux
```
sudo apt-get install tmux
```
# Sessions
Create new session / Создает новую сессию 
```
tmux new -s <name>
```

Kill all sessions / Убивает все сессии
```
tmux kill-server
```

Kill session / Убивает сессию испольузя имя
```
tmux kill-session -t <name>
```
Hotkeys / Горячие клавиши 
```
ctrl + b, x  - kill panel
```


# Split frame
Split Horizontal / Разделение по горизонтали
```
tmux split-window -hf
```
![enter image description here](https://github.com/Under4groos/Tmux/blob/master/Images/Horizontal_split.png?raw=true)

Split Verical / Разделение по вертикали
```
tmux split-window -vf
```
![enter image description here](https://github.com/Under4groos/Tmux/blob/master/Images/WindowsTerminal_9JRlAKUiey.png?raw=true)

Hotkeys / Горячие клавиши 
```
ctrl + b + % - to make a vertical split.
ctrl + b + " - to make a Horizontal split.
ctrl + b +   - left arrow to move to the left pane.
ctrl + b + " - to make a Horizontal split.
```