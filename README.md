win10的子系统下（WSL）挂载硬盘

```
# 新建文件夹e (如果/mnt下没有e的话)
sudo mkdir /mnt/e 
# 挂载e盘
sudo mount -t drvfs E: /mnt/e 
# 弹出移动硬盘
sudo umount /mnt/e 
# 这样硬盘才能在windows下正常弹出，否则是会一直占用的。 
```