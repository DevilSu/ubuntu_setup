# turn off bluetoooth while startup

Reference: https://itsfoss.com/turn-off-bluetooth-by-default-in-ubuntu-14-04/

## in terminal:
	1. sudo apt-get install gksu
	2. gksudo gedit /etc/rc.local
	3. insert "rfkill block bluetooth" before "exit 0"

(gksudo: run graphic as sudo, but can achieve with sudo also?)
