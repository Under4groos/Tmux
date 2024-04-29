
# My Base
```
sudo apt-get install
tmux new -s underko
tmux split-window -vf
```


# Install Tmux / Установка Tmux
```
sudo apt-get install tmux
```
# Sessions
List of sessions / Список сессий
``` 
tmux ls
```
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
"Ctrl-b, d" - Disconnect from the session
Отключиться от сессии

"ctrl + b, x"  - Kill panel
Закрыть панель

"ctrl + b, q"  - To show pane numbers
Показать нумерацию панелей

"ctrl + b, w"  - Shows a list of open windows
Показывает список открытых окон
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
"<" - left arrow / стрелка в лево 
">" - right arrow / стрелка в право 
```
```
"ctrl + >" Will move to the panel on the right
Переместится в панель с права 

"ctrl + <" Will move to the panel on the left
Переместится в панель с лево
```

# Sound play
```
Chanel METAHESH
```