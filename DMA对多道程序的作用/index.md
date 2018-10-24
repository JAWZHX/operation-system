# DMA对多道程序设计的作用

DMA(direc memory access): 直接存储器访问
多道程序设计的作用是让CPU的利用率明显增加，在某个程序等待I/O时，CPU可以做其他的事情。如果没有DMA，则CPU完全占用I/O，因此多道程序设计没有任何收益。