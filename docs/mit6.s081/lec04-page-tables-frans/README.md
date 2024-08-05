# Lec04 Page tables \(Frans\)

准备工作，阅读【1】中第3章；阅读memlayout.h【2】；阅读vm.c【3】；阅读kalloc【4】；阅读riscv.h【5】；阅读exec.c【6】



【1】[https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf](https://pdos.csail.mit.edu/6.828/2020/xv6/book-riscv-rev1.pdf)

【2】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/memlayout.h](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/memlayout.h)

【3】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/vm.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/vm.c)

【4】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/kalloc.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/kalloc.c)

【5】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/riscv.h](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/riscv.h)

【6】[https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/exec.c](https://github.com/mit-pdos/xv6-riscv/blob/riscv/kernel/exec.c)


* [4.1 课程内容简介](4.1-ke-cheng-nei-rong-jian-jie.md)
* [4.2 地址空间（Address Spaces）](4.2-di-zhi-kong-jian-address-spaces.md)
* [4.3 页表（Page Table）](4.3-ye-biao-page-table.md)
* [4.4 页表缓存（Translation Lookaside Buffer）](4.4-ye-biao-huan-cun-translation-lookaside-buffer.md)
* [4.5 Kernel Page Table](4.5-kernel-page-table.md)
* [4.6 kvminit 函数](4.6-kvminit-han-shu.md)
* [4.7 kvminithart 函数](4.7-kvminithart.md)
* [4.8 walk 函数](4.8-walk-han-shu.md)