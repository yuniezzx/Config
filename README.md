# oh my zsh

## git

####[Aliases ](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git#aliases)
常用命令
ga	git add
gaa	git add --all



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

## [extract](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/extract#extract-plugin)
该插件定义了一个名为 的函数，extract该函数提取您传递给它的存档文件，并且它支持多种存档文件类型。这样您就不必知道提取文件的具体命令，您只需要知道，
```
  extract <filename>
```
该函数就会处理其余的事情。


## themes

This plugin allows you to change ZSH theme on the go.

To use it, add themes to the plugins array in your zshrc file:

plugins=(... themes)

Usage

theme <theme_name> - Changes the ZSH theme to specified theme.

theme - Changes the ZSH theme to some random theme.

lstheme - Lists installed ZSH themes.

## zsh-syntax-highlighting 
提供高亮

## zsh-autosuggestions
Cmd 命令提示
