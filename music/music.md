# MUSIC
Install the required packages:
```
sudo pacman -S mpd ncmpcpp mpc
```
Create the configuration directories:
```
mkdir -p ~/.config/mpd ~/.config/ncmpcpp ~/.local/share/mpd/playlists
```
Copy the configuration files:
```
cp ~/{your_path}/mpd.conf ~/.config/mpd/mpd.conf
cp ~/{your_path}/ncmpcpp_config ~/.config/ncmpcpp/config
```
Replace {your_path} with the path to the directory that contains the configuration files.

If done just start the services:
```
systemctl --user start mpd
systemctl --user enable mpd
```
and run ncmpcpp, Press F1 inside ncmpcpp to open the help menu and view the available keybindings.
