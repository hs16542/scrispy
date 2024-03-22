# scrispy


很多脚本工具


## InstallAPP
- 避免每次敲击 覆盖安装、允许downgrade、allow test version

如果需要全局执行bash脚本可以

1. chmod +x InstallAPP.sh (mac可能需要brew install chmod)
2. 显示PATH环境变量（可以理解为shell查找命令的目录？）值 （echo $PATH）
     e.g. /opt/homebrew/bin:/opt/homebrew/sbin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin
   按：分隔 从前到后优先查找
3. mv InstallAPP.sh /usr/local/bin/installAPP
4. 后续直接在terminal输入installAPP xxx.apk 就可以了
5. 如果要实现自动补全 还需要另外安装并修改配置文件，需要再google吧。。
