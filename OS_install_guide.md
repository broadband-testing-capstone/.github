## Install Ubuntu on AMD64 Device

Usefull links:

1. Rufus (to create ubuntu install media) `https://rufus.ie/en/`
2. Ubuntu server (the OS we will be installing) `https://ubuntu.com/download/server`
3. Putty (assists in comunication over a com port) `https://www.putty.org/`
    * `use connection type: serial, speed: 115200n8`


## OS installation

Precondition: Device is turned off and connected via the management port to a machine with telnet/PuTTY installed

1. Insert Ubuntu 20.04 installation media into USB drive
2. Open telnet connection using the correct serial COM port and 115200 baud
3. Power on Lanner
4. When greeted with the grub bootloader, press `e` to edit the "Install" options
5. Change the line that begins with `linux` to add the following two flags before the triple hyphen `---`:
    * `console=tty0`
    * `console=ttyS0,115200n8`
6. Press `ctrl+X` to boot into the Ubuntu installer
7. Install the minimified version of the OS -- this will save space
8. When prompted about disk setup, deselect the option to use LVM
9. Use username `TODO` and password `TODO`
