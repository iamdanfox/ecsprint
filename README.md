ecsprint
========

Print files from your machine on the CS department printers.

**`./ecsprint m11dtf@ecs.ox.ac.uk report.txt`**


----------

#### Passwordless SSH Required

`ecsprint` copies files to the remote machine using `scp` and prints them using `ssh`.  You'll need [passwordless SSH][1] set up for this to work.

[1]: http://www.linuxproblem.org/art_9.html