# Lec06 Isolation & system call entry/exit \(Robert\)

准备工作：阅读【1】中第4章，除了4.6；阅读RISCV.h【2】；阅读trampoline.S【3】；阅读trap.c【4】



【1】[https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf)

【2】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/riscv.h](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/riscv.h)

【3】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/trampoline.S](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/trampoline.S)

【4】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/trap.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/trap.c)


* [6.1 Trap机制](6.1-trap.md)
* [6.2 Trap代码执行流程](6.2-trap-dai-ma-zhi-xing-liu-cheng.md)
* [6.3 ECALL指令之前的状态](6.3-before-ecall.md)
* [6.4 ECALL指令之后的状态](6.4-ecall-zhi-ling-zhi-hou-de-zhuang-tai.md)
* [6.5 uservec函数](6.5-uservec.md)
* [6.6 usertrap函数](6.6-usertrap.md)
* [6.7 usertrapret函数](6.7-usertrapret.md)
* [6.8 userret函数](6.8-userret.md)