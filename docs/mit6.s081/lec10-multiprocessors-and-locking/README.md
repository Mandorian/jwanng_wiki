# Lec10 Multiprocessors and locking \(Frans\)

准备工作，阅读【1】中第6章，和【2】

【1】[https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf)

【2】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/spinlock.h](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/spinlock.h)

【3】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/spinlock.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/spinlock.c)

* [10.1 为什么要使用锁？](10.1-why-lock.md)
* [10.2 锁如何避免race condition？](10.2-avoid-race-condition.md)
* [10.3 什么时候使用锁？](10.3-when-use-lock.md)
* [10.4 锁的特性和死锁](10.4-locks-properties-and-deadlock.md)
* [10.5 锁与性能](10.5-suo-yu-xing-neng.md)
* [10.6 XV6中UART模块对于锁的使用](10.6-case-study-uart.md)
* [10.7 自旋锁（Spin lock）的实现（一）](10.7-spin-lock-1.md)
* [10.8 自旋锁（Spin lock）的实现（二）](10.8-spin-lock-2.md)