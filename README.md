﻿ss-bash
=======

Shadowsocks流量管理脚本

* 目前只支持python版Shadowsocks
* 目前只支持统计ipv4流量

[英文版](https://github.com/hellofwy/ss-bash/tree/en)请见`en`分支，感谢[@Yaoshicn](https://github.com/Yaoshicn)的贡献。


[使用说明][User Manual]


[User Manual]:    https://github.com/hellofwy/ss-bash/wiki


定时清空流量任务
0 0 1 * * /bin/sh /root/ss-bash/ssadmin.sh reset_all_used >/root/temp.log 
