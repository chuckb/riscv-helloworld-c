# RISC-V Bare-Metal Hello World In C

## Prerequisites
This example and accompanying video were done on OSX. The tools were installed via homebrew. If the toolchain is installed on other OSes, then in theory it should also work, but I have not tested it.
- Compiler: https://github.com/riscv-software-src/homebrew-riscv
- Make
- QEMU: https://formulae.brew.sh/formula/qemu

## References:
- RISC-V From Scratch blog post: https://twilco.github.io/riscv-from-scratch/2019/04/27/riscv-from-scratch-2.html
- Everythng You Want to Know About Linker Scripts: https://mcyoung.xyz/2021/06/01/linker-script/#fn:not-main
- My Youtube video: https://youtu.be/HC7b1SVXoKM
- 16550 UART Documentation: https://www.ti.com/lit/ds/symlink/tl16c550d.pdf
- QEMU virt machine description: https://www.qemu.org/docs/master/system/riscv/virt.html

## Running:
`make run`