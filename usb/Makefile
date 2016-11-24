obj-m	:= usb-skeleton.o

KERNELDIR ?= /lib/modules/$(shell uname -r)/build
PWD       := $(shell pwd)

all:
	$(MAKE) -C $(KERNELDIR) M=$(PWD)

clean:
	rm -rf  *~ core *.mod.c *.mod.o *.ko *.o *.tmp_versions *.order *symvers *.unsigned .*.cmd .tmp_versions 

