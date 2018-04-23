#Writing ansible script.

Create a teacher and sysadmin group.

Create linux users Fred, and Barney. Fred is a teacher and Barney is a
sysadmin.

Check if /var/tmp/systemstat exists on the target machine. If it does, Copy
systemstat from that location into Fred’s home directory, and give it permissions
such that Fred is the only teacher who can write to it, and no other non-root user
can execute, read, or write to it.
