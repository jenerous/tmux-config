# tmux-config
my personal tmux config. Feel free to use it, if you like.
This is based on work of: [http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/]([http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/])

![example](example.png)


## Special Shortcuts

| shortcut | meaning |
| :------: | :-----: |
| ctrl + b |                      prefix |
| alt + ctrl + left  |    previous window |
| alt + ctrl + right |        next window |
| ctrl + arrow | switch pane in direction |

Mouse mode is enabled which means you can click panes or window tabs to focus them.

## Identify Current Host
I'm working on lot's of different machines. As I use this tmux config on all of it normally I get confused sometimes which one it is.
The config therefore includes the host name within the status bar and a colored block which's color comes from a simple hash over the hostname.
This let you recognize immediatly when on which machine you work right now.

## Usage
The repo contains two files. One is hidden for unix systems as it starts with a dot!
1. Clone the repo
2. copy .tmux.conf to your home directory
3. copy hashColor to a place within your path and ensure that it is executeable
4. use tmux with -2 flag! This enables 256 color support. I set an alias on my machines that maps tmux='tmux -2'
5. enjoy =)

## Detailed Installation Steps
```bash
git clone https://github.com/jhertfe/tmux-config.git
cd tmux-config
cp .tmux.conf ~/
# cp hostColor ~/bin/
```

To few your current Path use
```bash
echo $Path
```
