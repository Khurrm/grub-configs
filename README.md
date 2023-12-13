sudo vi /usr/share/grub/default/grub

sudo vi /etc/default/grub

sudo cp /usr/share/grub/default/grub /etc/default/grub


Change the following from Hidden to Menu
GRUB_DEFAULT="1>4"

GRUB_TIMEOUT_STYLE=hidden

GRUB_TIMEOUT_STYLE=menu

GRUB_TIMEOUT=10


Sudo update-grub

