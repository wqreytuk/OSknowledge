# 内存页

https://www.youtube.com/watch?v=w5TepY1S3N8

![image](https://github.com/wqreytuk/OSknowledge/assets/48377190/9b4a2a96-4a97-457c-bd56-14d1be0e369d)


p1|p2|...|d

这些都是偏移量，按照位置，p1就是第一个页表的偏移量，p2就是第二个页表的偏移量，以此类推

关键之处，就在于我们可以把用不到的内存页swap到磁盘中，如果都是在内存中，实际上多级页表占用的空间是变大的，由于我们可以把他们交换到硬盘中，就达到了节省内存空间的目的
