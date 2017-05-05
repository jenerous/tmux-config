# tmux-config
my personal tmux config. Feel free to use it, if you like.

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

## Detailed Install
Clone the repo
```bash
git clone https://github.com/jhertfe/tmux-config.git
cd tmux-config
cp .tmux.conf ~/
# cp hostColor ~/bin/
```
