usage:
1.g++ -o mmake mmake.cpp
2. ./mmake foo.cpp  (generate makefile,and foo.ko file)
To use the module,we need to do following steps
3.sudo insmod foo.ko
4.dmesg -c  (we can see the result)
5.sudo rmmod foo  (remove the module)

