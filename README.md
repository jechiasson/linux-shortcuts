# linux-shortcuts
# list of useful linux commands

# Systemd run level controls
# enable text mode boot
sudo systemctl set-default multi-user.target
# enable graphical (desktop) boot
sudo systemctl set-default graphical.target
# list current default
systemctl get-default
# To change to a different target unit in the current session only, run the following command:
sudo systemctl isolate runlevel3.target
