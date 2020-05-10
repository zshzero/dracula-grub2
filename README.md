# Dracula-Grub2
GRUB 2 Dracula Theme

## Installation
1. Extract the theme to /boot/grub/themes/

2. Edit /etc/default/grub file. Find the line starting with "#GRUB_THEME" and change it to "GRUB_THEME=/boot/grub/themes/dracula-grub2/theme.txt"

3. Run 
    ```sudo update-grub``` 
    Or 
    ```sudo grub-mkconfig -o /boot/grub/grub.cfg```

## Screenshot
![Screenshot](./Screenshot.png)

## License

[MIT License](./LICENSE)
