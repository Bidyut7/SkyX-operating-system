# SkyX Operating System

A hobbyist OS written in C++, built from scratch using a Multiboot2 bootloader, with QEMU for emulation. Initially prints text to the screen — will grow into multitasking, file system, networking, and GUI.

## Build & Run

```sh
mkdir -p build
make run
```

## Folder Structure

- src/boot: Assembly entry point
- src/kernel: C++ kernel logic
- build: Output directory
- Makefile: Build automation
- grub.cfg: GRUB boot config
- linker.ld: Linker script for binary layout

## Status

✅ Bootloader
✅ C++ Hello World Kernel
⬜ Interrupts
⬜ VGA & Keyboard Input
⬜ Memory Management
⬜ Multitasking
⬜ File System
⬜ GUI

