# Lec11 Thread switching \(Robert\)

准备工作，阅读【1】中7.1~7.4，阅读【2】【3】。

【1】[https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf)

【2】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/proc.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/proc.c)

【3】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/swtch.S](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/swtch.S)

* [11.1 线程（Thread）概述](11.1-thread.md)
* [11.2 XV6线程调度](11.2-xian-cheng-diao-du.md)
* [11.3 XV6线程切换（一）](11.3-xv6-thread-switching-1.md)
* [11.4 XV6线程切换（二）](11.4-xv6-thread-switching-2.md)
* [11.5 XV6进程切换示例程序](11.5-xv6-thread-switching-code.md)
* [11.6 XV6线程切换 --- yield/sched函数](11.6-yield-and-sched.md)
* [11.7 XV6线程切换 --- switch函数](11.7-xv6-switch-function.md)
* [11.8 XV6线程切换 --- scheduler函数](11.8-xv6-scheduler-function.md)
* [11.9 XV6线程第一次调用switch函数](11.9-xv6-call-switch-function-first-time.md)