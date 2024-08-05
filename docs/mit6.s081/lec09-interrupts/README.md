# Lec09 Interrupts \(Frans\)

准备工作，阅读【1】中第5章，以及【2-6】

【1】[https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf)

【2】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/kernelvec.S](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/kernelvec.S)

【3】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/plic.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/plic.c)

【4】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/console.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/console.c)

【5】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/uart.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/uart.c)

【6】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/printf.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/printf.c)

* [9.1 真实操作系统内存使用情况](9.1-memory-in-real-os.md)
* [9.2 Interrupt硬件部分](9.2-interrupt-handware.md)
* [9.3 设备驱动概述](9.3-device-driver.md)
* [9.4 在XV6中设置中断](9.4-xv6-set-interrupt.md)
* [9.5 UART驱动的top部分](9.5-uart-driver-top.md)
* [9.6 UART驱动的bottom部分](9.6-uart-driver-bottom.md)
* [9.7 Interrupt相关的并发](9.7-interrupt-related-concurrency.md)
* [9.8 UART读取键盘输入](9.8-uart-read-keyboard.md)
* [9.9 Interrupt的演进](9.9-interrupt-envolving.md)