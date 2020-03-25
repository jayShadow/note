
# vultr

<https://www.vultr.com>  

```
wget shiyu.pro/SSR && bash SSR  
rpm --import <https://www.elrepo.org/RPM-GPG-KEY-elrepo.org>  
rpm -Uvh <http://www.elrepo.org/elrepo-release-7.0-3.el7.elrepo.noarch.rpm>  
yum --enablerepo=elrepo-kernel install kernel-ml -y  
```

## 查看内核是否安装成功

```
rpm -qa | grep kernel
```

## 更新 grub 系统

```
egrep ^menuentry /etc/grub2.cfg | cut -f 2 -d \'
```

## default 0 表示第一个内核设置为默认运行, 选择最新内核就对了

```
grub2-set-default 0  
reboot  
```