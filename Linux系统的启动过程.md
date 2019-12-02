##linux 启动过程



###五个阶段

![](https://www.runoob.com/wp-content/uploads/2014/06/bg2013081707.png )
* 内核的引导
当计算机打开电源后，首先是BIOS开机自检，按照BIOS中设置的启动设备（通常是硬盘）来启动。操作系统接管硬件以后，首先读入 /boot 目录下的内核文件。

* 运行init
   * init类型
       * SysV :init,centos5之前，配置文件：/etc/inittab
       
       * Upstart:init,centos6，配置文件：/etc/inittab,/etc/init/*.conf
       * Systemd:systemd,centos7,配置文件：/etc/lib/systemd/system、/etc/systemd/system.
  
* 系统初始化

* 建立终端

* 用户登陆系统

