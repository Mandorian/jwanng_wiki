# Lec13 Sleep & Wake up \(Robert\)

准备工作，阅读【1】中7.5~7.10，阅读【2】【3】中相关部分。

【1】[https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf)

【2】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/proc.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/proc.c)

【3】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/sleeplock.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/sleeplock.c)

* [13.1 线程切换过程中锁的限制](13.1-lock-limitation-during-thread-switching.md)
* [13.2 Sleep&Wakeup 接口](13.2-sleep-wakeup.md)
* [13.3 Lost wakeup](13.3-lost-wakeup.md)
* [13.4 如何避免Lost wakeup](13.4-avoid-lock-wakeup.md)
* [13.5 Pipe中的sleep和wakeup](13.5-sleep-and-wakeup-in-pipe.md)
* [13.6 exit系统调用](13.6-exit-systemcall.md)
* [13.7 wait系统调用](13.7-wait-systemcall.md)
* [13.8 kill系统调用](13.8-kill-systemcall.md)