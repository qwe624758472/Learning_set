SOURCE=2
CC=nasm
LD=ld
TARGET=main

all:$(SOURCE).asm
	$(CC) -f elf $(SOURCE).asm
	$(LD) -m elf_i386 $(SOURCE).o -o $(TARGET)
	rm *.o
clean:
	rm $(TARGET)
