项目在day18里面的s21

2 用户名密码,也可以自己注册，然后登陆
用户名：hu
密码:123


3 实现的功能及其对应的url地址

----------------------------------------------------------- 关于用户的操作
注册
http://127.0.0.1:8000/register_user/

登录

http://127.0.0.1:8000/login/


查看用户列表（需要先登录才能查看）

http://127.0.0.1:8000/show_user/

添加用户（需要先登录才能添加）：

http://127.0.0.1:8000/add_user/

只要用户关闭浏览器（谷歌），或者退出登录，就需要重新登录才可以继续访问。
----------------------------------------------------------------关于主机的操作
查看主机列表（需要先登录）

http://127.0.0.1:8000/show_host/ 需要提前登录

在主机列表页面有添加，删除，编辑的功能

添加主机（需要先登录）

http://127.0.0.1:8000/add_host/
---------------------------------------------------------------关于业务的操作
查看业务列表

http://127.0.0.1:8000/show_service/（需要先登录）

列表里面有删除，添加，编辑的功能
-----------------------------------------------------------关于用户和业务关系的
查看用户和业务关系（需要先登录)

http://127.0.0.1:8000/user_service_list/

查看的页面有编辑的功能，没有添加和删除的功能，只可以添加，删除，用户或业务


![images](https://github.com/huningfei/cmdb-test-master/blob/master/images/host_list.png)
