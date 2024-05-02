
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

Для подключения к сессии 
```
tmux attach -t <name>
```

Kill all sessions / Убивает все сессии
```
tmux kill-server
```

Kill session / Убивает сессию испольузя имя
```
tmux kill-session -t <name>
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
 

```

```

Hotkeys / Горячие клавиши 
```
"<" - left arrow / стрелка в лево 
">" - right arrow / стрелка в право 

"Ctrl-b, d" - Disconnect from the session
Отключиться от сессии
"ctrl + b, x"  - Kill panel
Закрыть панель
"ctrl + b, q"  - To show pane numbers
Показать нумерацию панелей
"ctrl + b, w"  - Shows a list of open windows
Показывает список открытых окон
ctrl + > Will move to the panel on the right
Переместится в панель с права 
ctrl + < Will move to the panel on the left
Переместится в панель с лево

Ctrl+b c - создать новое окно;
Ctrl+b w - выбрать окно из списка;
Ctrl+b 0-9 - открыть окно по его номеру;
Ctrl+b , - переименовать текущее окно;
Ctrl+b % - разделить текущую панель по горизонтали;
Ctrl+b " - разделить текущую панель по вертикали;
Ctrl+b Ctrl+стрелка - изменить размер текущей панели;
Ctrl+b o - перейти на следующую панель;
Ctrl+b ; - переключаться между текущей и предыдущей панелью;
Ctrl+b x - закрыть текущую панель;
Ctrl+b [ - войти в режим копирования (подробнее ниже);
Ctrl+b ] - вставить из внутреннего буфера обмена tmux;
Ctrl+b d - отключится от текущей сессии;
Ctrl+b : - открыть командную строку.
```



# Sound play
```
Chanel METAHESH
```