# linux-shortcuts
list of useful linux commands

# Systemd run level controls
# enable text mode boot
systemctl set-default multi-user.target
# enable graphical (desktop) boot
systemctl set-default graphical.target
# list current default
systemctl get-default
# To change to a different target unit in the current session only, run the following command:
systemctl isolate runlevel3.target
