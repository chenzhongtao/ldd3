
FILES = nbtest load50 mapcmp polltest mapper setlevel setconsole inp outp \
	datasize dataalign netifdebug

KERNELDIR ?= /lib/modules/$(shell uname -r)/build
INCLUDEDIR = $(KERNELDIR)/include
CFLAGS = -O2 -fomit-frame-pointer -Wall -I$(INCLUDEDIR)

all: $(FILES)

clean:
    rm -rf  *~ core *.mod.c *.mod.o *.ko *.o *.tmp_versions *.order *symvers *.unsigned .*.cmd .tmp_versions 
	rm -f $(FILES) *~ core

