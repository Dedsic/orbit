# 关于orbit
本程序是将Tor-Browser-Bundle内置的firefox浏览器精简掉之后封装而成的代理工具. 其他程序可以通过socks端口将其作为数据前端(例如: Chrome+Switch Omega).  
你可以在这里查看torproject的原始代码[https://git.torproject.org]
  
# 使用
首先你需要知道你可以使用Tor Browser实现本项目所有的功能且无需复杂配置:[https://www.torproject.org/]  
即便如此也愿意尝试orbit请继续往下操作:  
Linux下需要先安装tor  
`apt install tor`  
使用cmd/bash运行  
`tor -f /location/of/torrc`(用你计算机上具体的tor配置文件路径替代)  
等待连接进度达到100%  
成功连接tor以后在需要用的程序当中设置代理.默认为socks5:localhost:9050  
  
注意: 默认的meet反射服务器由微软Azure提供,速度很慢甚至无法连接,且由于tor自身性质,orbit无法在相应速度等方面替代你的VPN或者ss服务.可以自行架设服务器以提高代理质量.  
  
# To do list
*编写一个能绕开权限的启动脚本  
*提供一个私人Meek反射服务器的部署方案改善响应速度  
