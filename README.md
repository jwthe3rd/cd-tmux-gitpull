# cd-tmux-gitpull
A shell script to use as a replacement for cd that will automagically load a new tmux session/window or attach to an existing session (session if not currently in a tmux session), (window if currently within a tmux session) at the passed directory, and check if this directory is a git repo, and if it is it will issue a new pull request at the current branch. Also, can pass a desired branch as the second argument (defaults to main)
