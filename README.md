# tmux shortcuts


tmux new-session  -s mysession

tmux kill-session -t mysession

tmux attach-session  -t mysession

# list all tmux sessions

tmux ls

ctrl + b "

ctrl + b %

## choose tmux session

tmux choose-tree



# tabs creation

ctrl + b c 

ctrl + b n (next tab)

ctrl + b x (close tab)

# navigation (replacement from mouse scroll)

ctril + b + [ or ]

Esc key to exit from navigation mode

![image](https://github.com/AltairZa/tmux-configuration/assets/14125075/c4c4fe5a-17c6-4ec0-b731-f462ac7f52ad)



 
## enable mouse:
set -g @plugin 'nhdaly/tmux-better-mouse-mode'
set -g mouse on

## copy content in tmux window

ctrl + shift + mouse selection

then use ctrl+shift+c

### alternative 

tmux-yank plugin

set -g @plugin 'tmux-plugins/tmux-yank'



# TMUX plugin manager installation :

https://github.com/tmux-plugins/tpm
ctrl + b + I : will result in updates of the plugins added in tmux configuraiton file


# Saving the session of TMUX

- tmux-continuum
- tmux-resurrect

  Above plugins are used to save the state of the session .. 


