These are customizations I made to the default Arch Linux systemd files.  They
should go into `/etc/systemd/system/`.

The old sysvinit scripts used to load most of their configuration from files in
/etc/conf.d, and I liked this approach.  I would much rather just edit these
files and restart a daemon than go and edit the *.service files as is it seems
is currently expected.
