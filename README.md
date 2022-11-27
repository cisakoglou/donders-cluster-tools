# donders-cluster-tools

## Schedule removal of logs - from the path as set by the user - every 24h

Add the following to ~/.bashrc file
>LOGDIR=$HOME/CODE/torque_logs/congrads
(LOGDIR indicates the folder where the logs from the cluster jobs are stored)
>AUTODIR=$HOME/CODE/donders-cluster-tools

>crontab $AUTODIR/jobs

And run 
source ~/.bashrc to reload

## Further examples of facilitating your work are contained in the .bashrc example file

