###执行构建：

```docker build -t alpine-jdk-8u333 .```

###说明

该镜像打包后大小为412m左右，包含常用的命令工具,中文，时区为上海，字体文件夹在/usr/share/fonts/

如果需要更小的jre环境，直接替换jdk为jre即可，并修改对应名称。Jre环境大小为310m左右

系统基础镜像采用dockerhub提供的alpine:latest系统镜像。
