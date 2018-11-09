all: compile qemu

qemu:
	qemu-system-i386 -fda boot.bin
compile:
	nasm boot.asm -f bin -o boot.bin
clean:
	rm boot.bin
