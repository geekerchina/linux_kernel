kernel programming test
=======================
#build
make

#run
sudo insmod hellointerrupt.o irq=1 devname=myirq
sudo rmmod hellointerrupt

#show result
dmesg

#contact
liuhm09@gmail.com

#original source code
http://edsionte.com/techblog/archives/1521
