# 下载安装包

[官网地址](https://www.scala-lang.org/download/2.12.16.html)

下载完成后，解压

# 配置环境变量

```
cd

vim .zshrc

SCALA_HOME=/Users/{用户目录}/scala-2.12.16
PATH=$PATH:$SCALA_HOME/bin
export SCALA_HOME
export PATH

source .zshrc
```

# 验证

```
scala
```