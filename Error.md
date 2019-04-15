
MIPv6平台搭建的问题记录：

1、当测试MIPv6程序时，遇到一个问题：

截取一部分信息：
xfrm_cn_init:Adding policies and states for CN
Failed to add policy
nlmsg_flags 405
nlmsg_type 19 

解决：在查看资料和源码后，初步认为内核配置并没有成功，也就是内核不支持XFRM

参考：https://support.ml.nautilus6.narkive.com/YO3iFPEV/mip6d-errors