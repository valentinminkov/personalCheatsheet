# Cheatsheet Personal Notes 

*This is a living document that will be continuously updated with new information.*

## **Table of Contents**

- [Linux](#linux)
  - [KDE](#kde)
    - [Restarting Plasma in KDE](#restarting-plasma-in-kde)
  - [Services](#services)
    - [Restarting Bluetooth Service](#restarting-bluetooth-service)
- [Vim](#vim)
  - [Basic Vim Cheatsheet](#basic-vim-cheatsheet)
- [Tmux](#tmux)
  - [Basic Tmux Cheatsheet](#basic-tmux-cheatsheet)

---

# **Linux**

*Various Linux related information, tips and tricks.*

## **KDE**

*This section deals with the KDE desktop environment on Linux.*

### **Restarting Plasma in KDE**

1. Enter the following command to kill the Plasma shell:
``` 
killall plasmashell
```

2. Restart it by running the following command:

```
kstart5 plasmashell
```

## **Services**

*This section deals with services on Linux.*

### **Restarting Bluetooth Service**

``` 
sudo systemctl restart bluetooth
```

# **Vim**


## **Basic Vim cheatsheet**

| Command | Description |
| ------- | ----------- |
| `i` | Enter insert mode |
| `esc` | Return to command mode |
| `:w` | Save file |
| `:q` | Quit Vim |
| `:wq` or `:x` | Save and quit |
| `:q!` | Quit without saving |
| `dd` | Delete line |
| `yy` | Copy line |
| `p` | Paste |
| `/text` | Search for 'text' |
| `n` | Jump to next search result |
| `u` | Undo last change |
| `Ctrl + r` | Redo last undone change |
| `v` | Start visual selection |
| `y` | Yank (copy) highlighted text |
| `:s/foo/bar/g` | Replace 'foo' with 'bar' in the current line |
| `:%s/foo/bar/g` | Replace 'foo' with 'bar' in the entire file |
| `"*p` | Paste from clipboard, replacing the current selection |
| `"*y` | Copy highlighted text to the clipboard |

# **Tmux**

## **Basic Tmux Cheatsheet**

| Command | Description |
| ------- | ----------- |
| `tmux` | Start a new tmux session |
| `tmux new -s myname` | Start a new tmux session named myname |
| `tmux a` or `tmux at` | Attach to the last used tmux session |
| `tmux a -t myname` | Attach to the tmux session named myname |
| `tmux ls` | List all tmux sessions |
| `tmux kill-session -t myname` | Kill the tmux session named myname |
| `Ctrl+b "` | Split

 the current pane into two, top and bottom |
| `Ctrl+b %` | Split the current pane into two, left and right |
| `Ctrl+b arrow key` | Navigate through panes |
| `Ctrl+b d` | Detach from the current tmux session |
| `Ctrl+b c` | Create a new window |
| `Ctrl+b n` | Move to the next window |
| `Ctrl+b p` | Move to the previous window |
| `Ctrl+b l` | Move to the last window |


---

