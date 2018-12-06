# Dual system time difference fixed (win10, ubuntu)

Reference: https://www.howtogeek.com/323390/how-to-fix-windows-and-linux-showing-different-times-when-dual-booting/

## In terminal:

1. `timedatectl set-local-rtc 1 --adjust-system-clock`
2. `timedatectl`,  check if trc is set as yes