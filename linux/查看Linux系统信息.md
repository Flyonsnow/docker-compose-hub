# Bench.sh

查看您的 Linux 系统信息，还可以测试网络带宽及硬盘读写速率

```shell
curl -Lso- bench.sh | bash
```

或者

```
wget -qO- bench.sh | bash
```



示例结果

```shell
-------------------- A Bench.sh Script By Teddysun -------------------
 Version            : v2022-06-01
 Usage              : wget -qO- bench.sh | bash
----------------------------------------------------------------------
 CPU Model          : Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
 CPU Cores          : 8 @ 800.024 MHz
 CPU Cache          : 6144 KB
 AES-NI             : Enabled
 VM-x/AMD-V         : Enabled
 Total Disk         : 449.8 GB (2.5 GB Used)
 Total Mem          : 31.3 GB (370.9 MB Used)
 Total Swap         : 15.7 GB (0 Used)
 System uptime      : 1 days, 2 hour 31 min
 Load average       : 0.00, 0.01, 0.05
 OS                 : CentOS Linux release 7.6.1810 (Core)
 Arch               : x86_64 (64 Bit)
 Kernel             : 3.10.0-957.el7.x86_64
 TCP CC             : cubic
 Virtualization     : Dedicated
 Organization       : AS4134 CHINANET-BACKBONE
 Location           : Nanjing / CN
 Region             : Jiangsu
----------------------------------------------------------------------
 I/O Speed(1st run) : 428 MB/s
 I/O Speed(2nd run) : 424 MB/s
 I/O Speed(3rd run) : 425 MB/s
 I/O Speed(average) : 425.7 MB/s
----------------------------------------------------------------------
```

