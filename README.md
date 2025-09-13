# Save-and-load-Ubuntu-24.04-terminal-Color-scheme
How to save and load your Ubuntu 24.04 terminal color scheme

Instructions:

Save color profile

`dconf dump /org/gnome/terminal/legacy/profiles:/ > gnome-terminal-profiles.dconf`

Load color profile

`dconf load /org/gnome/terminal/legacy/profiles:/ < gnome-terminal-profiles.dconf`
