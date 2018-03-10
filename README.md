# how-linux-works

```
$ sudo apt install binutils build-essential sysstat
```

```
$ uname -a
Linux ubuntu 4.13.0-36-generic #40~16.04.1-Ubuntu SMP Fri Feb 16 23:25:58 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux
```

```
$ lshw -short
H/W path        Device     Class          Description
=====================================================
                           system         To Be Filled By O.E.M. (To Be Filled By O.E.M.)
/0                         bus            Z170M Pro4S
/0/0                       memory         64KiB BIOS
/0/c                       memory         128KiB L1 cache
/0/d                       memory         128KiB L1 cache
/0/e                       memory         1MiB L2 cache
/0/f                       memory         8MiB L3 cache
/0/10                      processor      Intel(R) Core(TM) i7-6700K CPU @ 4.00GHz
/0/11                      memory         16GiB System Memory
/0/11/0                    memory         DIMM [empty]
/0/11/1                    memory         8GiB DIMM Synchronous 2133 MHz (0.5 ns)
/0/11/2                    memory         DIMM [empty]
/0/11/3                    memory         8GiB DIMM Synchronous 2133 MHz (0.5 ns)
/0/100                     bridge         Sky Lake Host Bridge/DRAM Registers
/0/100/1                   bridge         Sky Lake PCIe Controller (x16)
/0/100/1/0                 display        NVIDIA Corporation
/0/100/1/0.1               multimedia     NVIDIA Corporation
/0/100/14                  bus            Sunrise Point-H USB 3.0 xHCI Controller
/0/100/14/0     usb1       bus            xHCI Host Controller
/0/100/14/0/9              input          Sensei Wireless Gaming Mouse
/0/100/14/0/b              generic        Controller
/0/100/14/0/c              communication  CSR8510 A10
/0/100/14/0/d              input          Realforce 91
/0/100/14/1     usb2       bus            xHCI Host Controller
/0/100/14.2                generic        Sunrise Point-H Thermal subsystem
/0/100/16                  communication  Sunrise Point-H CSME HECI #1
/0/100/17                  storage        Sunrise Point-H SATA controller [AHCI mode]
/0/100/1b                  bridge         Sunrise Point-H PCI Root Port #17
/0/100/1c                  bridge         Sunrise Point-H PCI Express Root Port #1
/0/100/1d                  bridge         Sunrise Point-H PCI Express Root Port #9
/0/100/1f                  bridge         Sunrise Point-H LPC Controller
/0/100/1f.2                memory         Memory controller
/0/100/1f.3                multimedia     Sunrise Point-H HD Audio
/0/100/1f.4                bus            Sunrise Point-H SMBus
/0/100/1f.6     enp0s31f6  network        Ethernet Connection (2) I219-V
/0/1            scsi0      storage        
/0/1/0.0.0      /dev/sda   disk           250GB Crucial_CT250MX2
/0/1/0.0.0/1    /dev/sda1  volume         500MiB Windows NTFS volume
/0/1/0.0.0/2    /dev/sda2  volume         231GiB Windows NTFS volume
/0/1/0.0.0/3    /dev/sda3  volume         505MiB Windows NTFS volume
/0/2            scsi1      storage        
/0/2/0.0.0      /dev/sdb   disk           480GB CT480BX200SSD1
/0/2/0.0.0/1    /dev/sdb1  volume         447GiB Windows NTFS volume
/0/3            scsi5      storage        
/0/3/0.0.0      /dev/sdc   disk           480GB CT480BX200SSD1
/0/3/0.0.0/1    /dev/sdc1  volume         432GiB Extended partition
/0/3/0.0.0/1/5  /dev/sdc5  volume         432GiB Linux filesystem partition
/0/3/0.0.0/2    /dev/sdc2  volume         14GiB Linux swap volume
```
