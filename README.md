# susage

This script provide convenient ways to list or summarize SLURM queued jobs or idle nodes.

Usage: `susage <COMMAND>`

select a command from:
* use:   show usage summary of each node
* my:    list all your own queued jobs
* all:   list all the queued jobs
* sum:   sum queued jobs by users and state
* nsum:  sum running jobs by nodes and users
* idle:  list nodes and CPUs on idle (i.e. currently accepting jobs)

Author: Guillaume Lentendu <guillaume.lentendu@unine.ch>
