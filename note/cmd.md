## windows   cmd命令

##### 关闭登录密码

```
Control Userpasswords2
```

##### 复制、移动文件

```
// 复制指定文件
copy d:\1\1.txt f:\1\
// 复制目录下所有文件
copy d:\1\*.* d:\1\123
// 移动所有文件（进入指定目录）
move * f:\1\
```

##### 文件删除

```
// 删除aa下所有空文件夹
rd f:\aa
// 删除aa下所有文件
DEL f:\aa\*.*
// 删除aa目录下所有目录文件
RD /S f:\aa
```

##### 文件查看

```
// aa目录下查看文件树状图
tree f:\aa
```

