bin文件用的是：http://www.hostloc.com/thread-307291-1-1.html

安装文件用的是：http://www.hostloc.com/thread-307201-1-1.html

lic授权生成用的是：http://www.hostloc.com/thread-307224-1-1.html


功能：
如果内核完全匹配就会自动下载安装。
如果没有完全匹配的内核，会在界面提示可选内核，可以手动选个最接近的尝试
自动下载授权文件
自动修改配置文件
已chattr +i /serverspeeder/etc/apx*禁止修改配置文件，可以不用加hosts了
目前只支持CentOS，ubuntu和debian。如果有其他系统支持，可以到http://www.91yun.org/serverspeeder91yun手动下载其他系统的安装包

使用方法：

wget https://github.com/dragon-tang/serverspeeder/blob/master/serverspeeder-all.sh && bash serverspeeder-all.sh



卸载方法：
chattr -i /serverspeeder/etc/apx*  &&  /serverspeeder/bin/serverSpeeder.sh uninstall -f

