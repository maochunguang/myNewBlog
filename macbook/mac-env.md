# mac环境问题

### 1、mac升级后找不到python

原因：mac新版本不再按照python，默认安装的是python3。

解决方法：创建一个软连接，把python指向python3。

```bash
sudo ln -s /Library/Developer/CommandLineTools/Library/Frameworks/Python3.framework/Versions/3.8/bin/python3.8 /usr/local/bin/python3

sudo ln -s -f /usr/local/bin/python3 /usr/local/bin/python
```


执行以上两行命令，会在/usr/local/bin/目录下生成，python3与python的快捷引用方式；

> 注意：`/Library/Developer/CommandLineTools/Library/Frameworks/Python3.framework/Versions/3.8`为你的python目录，不一定是3.8，也可能是3.9，取决于你的mac版本。
