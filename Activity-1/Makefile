
CC =arm-none-eabi-gcc
MACH=cortex-m4
CFLAGS= -c -mcpu=$(MACH) -mthumb -std=gnu11 -o0

lastdigit.o:lastdigit.c
	$(CC) $(CFLAGS) -o $@ $^