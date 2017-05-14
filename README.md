# scanlan_ip
#-*- coding: utf-8 -*-  
#author: orangleliu  date: 2014-11-12   
#python3 by 0han date: 2016.9.9
#python3.x scanlanip.py

Its aim to scan the dynamic ip address from the range 192.168.0.1-225
command:
`python3 scanlanip.py 192.168.1.1`



旨在扫描局域网内192.168.0.1-225网段存活主机内网ip，作者是orangleliu，由0han改为python3的版本，后期会持续更新
运行方法（注释中也有）：
"""
不同平台，实现对所在内网端的ip扫描
有时需要知道所在局域网的有效IP地址，但是又不想找特定的工具来扫描。 
使用方法 python3 scanlanip.py 192.168.1.1  
(会扫描192.168.1.1-255的ip) 
"""
