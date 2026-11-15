# kitty-terminal-configuration-hyprland
the hyprland kitty terminal for your gnome or kde desktops 
 install a image which you interested and save it in home/pictures/image.png 
 using 
 step 1.sudo dnf install ImageMagick -y 
 in terminal enter this 
 step 2.magick ~/Pictures/Your_image.png -fuzz 10% -fill none -draw "alpha 0,0 floodfill" ~/Pictures/Your_image.png
