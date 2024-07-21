# RISC-V Bare-Metal Hello World In C
As simple as I could make it bare metal C application writing Hello World! to the serial port of the QEMU virt machine, including debug setup for GDB and VSCode.
 
This repo is accompanied by two youtube videos:
- RISC-V Bare-Metal Hello World In C: https://youtu.be/HC7b1SVXoKM
- RISC-V Debugging With QEMU, GDB, and VSCode: https://youtu.be/NbZDowmXzZs
- Tags in the repo are named by video if you want to have code versioned as such.

## Prerequisites
This example and accompanying video were done on OSX. The tools were installed via homebrew. If the toolchain is installed on other OSes, then in theory it should also work, but I have not tested it.
- Compiler: https://github.com/riscv-software-src/homebrew-riscv
- Make
- QEMU: https://formulae.brew.sh/formula/qemu
- VSCode
- GDB or Debugger from Risc-V Toolchain if available on your platform (was not bottled in homebrew)

## References:
- RISC-V From Scratch blog post: https://twilco.github.io/riscv-from-scratch/2019/04/27/riscv-from-scratch-2.html
- Everythng You Want to Know About Linker Scripts: https://mcyoung.xyz/2021/06/01/linker-script/#fn:not-main
- 16550 UART Documentation: https://www.ti.com/lit/ds/symlink/tl16c550d.pdf
- QEMU virt machine description: https://www.qemu.org/docs/master/system/riscv/virt.html
- QEMU GDB usage: https://www.qemu.org/docs/master/system/gdb.html
- QEMU full boot process: https://popovicu.com/posts/risc-v-sbi-and-full-boot-process/
- FreeRTOS debug example: https://github.com/FreeRTOS/FreeRTOS/tree/main/FreeRTOS/Demo/CORTEX_MPS2_QEMU_IAR_GCC

## Running:
`make debug` for GDB client
or
run `Debug RISC-V` from VSCode debug menu