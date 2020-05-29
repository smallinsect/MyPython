# MyPython

# Linux安装

下载链接

```
https://www.python.org/downloads/source/
```

下载

```
wget https://www.python.org/ftp/python/3.8.3/Python-3.8.3.tgz
```

解压压缩包

```
tar -xzf Python-3.8.3.tgz
进入文件 cd Python-3.8.3
```

安装

```
进入文件 cd Python-3.8.3
执行 ./configure 脚本
make
make install
```

配置环境变量

```
# 习惯用vim，没有的话可以用命令`sudo apt-get install vim`安装一个
vim /etc/profile
# 在最后一行添加
export PATH=$PATH:/usr/local/bin/python3
# 保存退出后source一下（vim 的使用方法可以自己搜索一下）
source /etc/profile
```

