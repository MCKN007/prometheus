# prometheus 普罗米修斯计划
关于为什么起这个么个名字：普罗米修斯是古希腊的神之一，人教版小学课本中有一篇他的文章，说他从太阳神阿波罗那里盗取了火种带到了人间，给人间带来光明，是人类不在茹毛饮血，而这个程序则是帮助你从单位机构手里面获取食物帮助苦逼的你减少经济上的负担

# 这个程序如何使用？
这个程序是在Linux上才能运行的而且是apt包管理器的系统
你需要运行安装文件，这需要系统最高权限，所以操作全部在root模式下进行
使用方法：
```shell
1. git clone https://github.com/MCKN007/prometheus-lua.git
2. cd prometheus
3. ./install
```
软请确保软件第一次运行时连接网络，需要下载必须的库
```shell

输入1是运行卡片扫描程序,也就是扫描卡片类型这里是使用os.execute函数去调用系统执行命令扫描ic卡
输入2是读取卡片内容并且保存为文件方便你以后的写入和对密钥的读取
输入3是把你想要写入的数据写入到IC卡里面，第一次输入的是要写入文件的路径，第二次输入的是米要文件的路径
输入4是使用mfcuk暴力破解密钥，然后你可以利用暴力破解来的密钥配合mfoc去使用
输入5是使用bless编辑读取的数据文件
输入6是删除软件
```
#### 软件的下载地址
```
https://github.com/MCKN007/prometheus-lua/releases/
````
第一个是命令行版本，第二个是带图形化界面的版本

 [捐赠墙(点击查看)](/donors.md)
