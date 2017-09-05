# uwsgi
## 概念
uWSGI可以理解成`应用服务器`（类比nginx是`web服务器`），它实现了WSGI协议、uwsgi、http等协议。
> 注意：uWSGI和uwsgi不是一个东西，uwsgi是协议，具体参考[这篇文章](http://www.jianshu.com/p/679dee0a4193)

## 安装&编译
```
# 1. 下载tar包&解压
wget https://projects.unbit.it/downloads/uwsgi-2.0.13.1.tar.gz
tar zxvf uwsgi-2.0.13.1.tar.gz
# 2. 安装
cd uwsgi-2.0.13.1/
python uwsgiconfig.py --build
```

