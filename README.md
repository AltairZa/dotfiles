# tmux shortcuts


tmux new-session  -s mysession

tmux kill-session -t mysession

tmux attach-session  -t mysession

# list all tmux sessions

tmux ls

ctrl + b "

ctrl + b %

# tabs creation

ctrl + b c 

ctrl + b n (next tab)

ctrl + b x (close tab)

# navigation (replacement from mouse scroll)

ctril + b + [ or ]

Esc key to exit from navigation mode

# archive
## enable mouse:
setw -g mouse on
## copy content in tmux window
ctrl + shift + mouse selection
then use ctrl+shift+c
