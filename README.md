# Setting up Sway

## Ubuntu 24.04
* Use Gnome with GDM as base. 
* On Ubuntu an importan XDG portal is missing: `sudo apt install xdg-desktop-portal-wlr`
	* Without this portal waybar does not work
	* Activate in sway config with: `exec dbus-update-activation-environment --systemd WAYLAND_DISPLAY XDG_CURRENT_DESKTOP=swa`

### Installation shortcut
```bash
sudo apt install sway waybar kitty wofi sway-notification-center kanshi \ 
blueman network-manager-gnome grim slurp swaylock fonts-font-awesome \
ranger xdg-desktop-portal-wlr \
thunar thunar-archive-plugin gvfs gvfs-backends \
pavucontrol
```
