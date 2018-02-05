# [lsblk]()教程

## 概述



## 相关命令

`fdisk -l`

<pre>
partprobe

pvcreate /dev/sda4

vgs

vgextend vg_sys /dev/sda4

lvextend -L +64G /dev/mapper/vg_sys-lv_root

vgchange -a y vg_sys

resize2fs /dev/mapper/vg_sys-lv_root


</pre>




## 生产案例







## 引用


[]()

[]()

[]()
