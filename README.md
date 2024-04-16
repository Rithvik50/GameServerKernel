# GameServerKernel
This is a C file and a Makefile that creates a game server Linux kernel. To run the kernel, run the following commands in Terminal:

make
sudo insmod gameserver.ko
sudo dmesg
sudo rmmod gameserver.ko
sudo dmesg -c
