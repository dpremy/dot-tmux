# tmux cheatsheet

## Session Management

| Key                        | Comment  |
| ---                        | --- |
| tmux attach                | Attach to last session |
| tmux attach -t _name_      | Attach to session _name_ |
| :new-session               | Start a new session |
| :new -s _name_             | Start a new session with _name_ |
| :kill-session -t _name_    | Kill/delete session _name_ |
| :kill-session -a           | kill/delete all sessions but the current |
| :kill-session -a -t _name_ | kill/delete all sessions but _name_ |
| ` $                        | Rename session |
| ` d                        | Detach from session |
| ` D                        | Choose client to detach |
| ` s                        | Attach to session |
| ` (                        | Switch client toprevious session |
| ` )                        | Switch client tonext session |

## Window Management

| Key               | Comment  |
| ---               | --- |
| ` c               | Create new window |
| ` r               | Rename current window |
| ` k               | Kill current window |
| ` p               | Previous window |
| ` n               | Next window |
| ` L               | Toggle to last active window |
| ` w               | List windows |
| ` f               | Find window by name |
| ` F               | Make current window the first window |
| ` 0...9           | Switch/select window by number |
| ` <>              | Move current window to the left or right by one |

## Pane Management
| Key             | Comment  |
| ---             | --- |
| ` |             | Split pane vertically |
| ` -             | Split pane horizontally |
| ` {             | Swap pane with previous |
| ` }             | Swap pane with next |
| ` ←→↑↓          | Switch to pane in direction |
| ` S             | Toggle synchronize-panes(send commands to all panes) |
| ` h             | Switch to horizontal layout |
| ` v             | Switch to vertical layout |
| ` Spacebar      | Toggle pane layout |
| ` l             | Toggle to last active pane |
| ` #             | Display pane numbers |
| ` # 0…9         | Switch to pane by number |
| ` z             | Toggle pane zoom |
| ` !             | Break pane to new window |
| ` m             | Mark the current pane |
| ` M             | Clear the current mark |
| ` x             | Close current pane |
| ` Ctrl + ↑↓     | Resize current pane height |
| ` Ctrl + ←→     | Resize current pane width |
| ` Alt + ↑↓      | Resize current pane by 5 height |
| ` Alt + ←→      | Resize current pane by 5 width |

## Misc.

| Key             | Comment  |
| ---             | --- |
| ` :             | Enter command mode |
| ` t             | Display a clock |
| ` R             | Reload .tmux.conf |
| :setw -g OPTION | Set OPTION for all windows |
| :set -g OPTION  | Set OPTION for all sessions |

## Help

| Key   | Comment  |
| ---   | --- |
| :info | Show every session, window, pane, etc. |
| ` ?   | Show keyboard shortcuts |

## Copy Mode

| Key                     | Comment  |
| ---                     | --- |
| ` Esc                   | Enter copy mode |
| ` PgUp                  | Enter copy mode and scroll up one page |
| q                       | Quit mode |
| g                       | Go to top line |
| G                       | Go to bottom line |
| ↑                       | Scroll up |
| ↓                       | Scroll down |
| /                       | Search forward |
| ?                       | Search backward |
| n                       | Next keyword occurrence |
| N                       | Previous keyword occurrence |
| v                       | Start selection |
| V                       | Start line selection |
| Esc                     | Clear selection |
| y                       | Copy selection |
| ` B                     | List all buffers |
| ` b                     | Show all buffers and paste selected |
| ` p                     | Paste contents of buffer\_0 |
| :show-buffer            | Display buffer\_0 |
| :capture-pane           | Copy entire visible contents of pane to buffer |
| :save-buffer _file.txt_ | Save buffer contents to _file.txt_ |
| :delete-buffer -b 0…9   | Delete buffer by number |

## Version

1/29/2022

To be used in conjunction with dpremy’s tmux dotfiles - https://gitlab.com/dpremy/dot-tmux/
