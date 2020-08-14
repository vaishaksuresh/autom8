# A Collection on utilities to automate iTerm

## MultiPane.scpt

Apple script that does the following

1. Takes a line separated server list as argument
2. Opens a new Iterm Window
3. Makes the terminal full screen
4. If there are 2 or more servers, splits the terminal horizontally
5. SSH into first half of the servers on the top pane and second half in the bottom pane
6. Each SSH is in its own pane

How to run

`$ osascript MultiPane.scpt /Users/vsuresh/servers/servers.txt`
