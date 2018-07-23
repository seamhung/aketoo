# centos 基本性能检查

查看系统版本
```shell
lsb_release -a
```

查看内核版本
```shell
uname -a
```

查看 CPU信息
```shell
lscpu
```

查看内存信息
```shell
free -h
```

查看磁盘信息
```shell
fdisk -h
df -h /

# 查看目录大小
du -h --max-depth=1 /
```


查看启动项
```shell

```

查看网络信息
```shell
chkconfig list
```
