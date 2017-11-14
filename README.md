# 关于orbit
本程序是将Tor-Browser-Bundle内置的firefox浏览器精简掉之后封装而成的代理工具. 其他程序可以通过socks端口将其作为数据前端(例如: Chrome+Switch Omega). 

# 使用
Linux下需要先安装tor
<apt install tor>
使用bash进入到根目录以后，执行
<tor -f /location/of/torrc>(用你计算机上具体的文件路径替代)

# To do list
*解决Windows下完美闪退的问题
*编写一个能绕开权限的启动脚本
*提供一个私人Meek反射服务器的部署方案改善响应速度