环境配置：

首先要求：python 3.6
响应的库函数：matplotlib ，python-scapy，logging，threading，python-nmap
本机需要安装的程序：nmap
cript-vulscan配置参考：https://www.jianshu.com/p/3bc47bb361f8


Finger_os.py:
	该文件是用来探测操作系统的，其中有一种是基于nmap修改的扫描探测方式。另一种是基于ttl的探测。默认是ttl	的。（配置：需要修改nmap_os_db的位置为本机的相应的位置）
Scanport.py：
	该文件是用来探测开放端口信息的
Ip_bug.py：
	该文件是用来探测常见的漏洞的。（需要配置script-vulscan）
Mac.py：
	该文件是用来探测mac地址的
Firewall.py：
	该文件是用来探测防火墙状态的
Antivirus_softwar.py：
	该文件是用来探测杀毒软件的
Scanip.py：
	该文件是用来处理接受的输入同时扫描在线的ip主机并进行排序
all_information.py：
	该文件是将以上的信息进行整合的代码
UI.py：
	该文件是实现UI界面
Main.py：
	主函数的执行入口
