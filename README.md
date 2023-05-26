## Hyprland-v2.2
- An slight upgrade from v2.1 which includes installation of Catppuccin Mocha and Latte GTK themes. 
- This can be use to directly upgrade Hyprland-v2.1 config files.

- For those who are using my other config files: (Hyprland-v2, HyprLanD and Ja_Hyprland_dots); see below for guidance
- a) easiest way is to upgrade to Hyprland-v2.1 first. and then ran this small upgrade. This is because this script is checking the dark and light folders, which contains a dark and light wallpapers.
- b) if decided not to upgrade to v2.1, download the wallpapers folder from Hyprland-v2.1, place it to your ~/Pictures/wallpapers. Make a backup of your ~/.config/hypr, rename it to like ~/.config/hypr-backup. Copy the hypr folder from this repo to your ~/.config/hypr , overwriting the files needed. Once copied, Make all new scripts from this repo executable by running chmod +x dark-light-mode , chmod +x layout-switcher, chmod +x waybar-style-change.

## Steps
- clone this repo https://github.com/JaKooLit/Hyprland-v2.2.git
- cd Hyprland-v2.2
- chmod +x upgrade-v2.2
- ./upgrade-v2.2



## to revert, or uninstall this upgrade.

-a.) uninstall packages catppuccin-gtk-theme-mocha and catppuccin-gtk-theme-latte by running in your terminal ```sudo pacman -R catppuccin-gtk-theme-mocha catppuccin-gtk-theme-latte```
  
-b.) If ~/.config/hypr-backup is present, simply delete ~/.config/hypr and rename the ~/.config/hypr-backup to ~/.config/hypr


## Long term notes
- if there are small upgrades in the future, I will continue using the Hyprland-v2.1 layouts so you dont need to move around much on your configs especially the wallpaper files.
