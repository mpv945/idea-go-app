# idea-go-app  [中文社区](https://studygolang.com/)
我的go应用

# 安装环境     官网地址 https://golang.org 
  1. 解压，配置GOROOT:D:\soft\go 变量；增加path:%GOROOT%\bin;Linux, macOS, and FreeBSD安装：tar -C /usr/local -xzf go$VERSION.$OS-$ARCH.tar.gz；然后系统或者用户的$HOME/.profile增加export PATH=$PATH:/usr/local/go/bin；最后让环境变量生效：source $HOME/.profile；最后执行go env验证是否安装成。
  2. 安装iris框架（web）： go get -u github.com/kataras/iris 中间可能要十几分钟

# idea 安装go插件，然后新建项目。可以右键运行代码；new --> file(可以选择【Go file】 的 Simple Application可以生成简单代码骨架
