# oh my zsh

## tmux

#### [Aliases](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/tmux#aliases)

| Alias      | Command                    | Description                                              |
| ---------- | -------------------------- | -------------------------------------------------------- |
| `ta`       | tmux attach -t             | Attach new tmux session to already running named session |
| `tad`      | tmux attach -d -t          | Detach named tmux session                                |
| `ts`       | tmux new-session -s        | Create a new named tmux session                          |
| `tl`       | tmux list-sessions         | Displays a list of running tmux sessions                 |
| `tksv`     | tmux kill-server           | Terminate all running tmux sessions                      |
| `tkss`     | tmux kill-session -t       | Terminate named running tmux session                     |
| `tmux`     | `_zsh_tmux_plugin_run`     | Start a new tmux session                                 |
| `tmuxconf` | `$EDITOR $ZSH_TMUX_CONFIG` | Open .tmux.conf file with an editor                      |