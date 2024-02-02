# cd-tmux-gitpull
A shell script to use as a replacement for cd that will automagically load a new tmux window at the passed directory, and check if this directory is a git repo, and if it is it will issue a new pull request at the current branch. Also, can pass a desired branch via some command line argument, maybe "-b"
