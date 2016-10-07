##XSS攻击的危害包括
- 1、盗取各类用户帐号，如机器登录帐号、用户网银帐号、各类管理员帐号
- 2、控制企业数据，包括读取、篡改、添加、删除企业敏感数据的能力
- 3、盗窃企业重要的具有商业价值的资料
- 4、非法转账
- 5、强制发送电子邮件
- 6、网站挂马
- 7、控制受害者机器向其它网站发起攻击
- 弹出cookies，挂马等
- 劫持会话，执行任意操作
- 刷流量，执行弹窗广告
- 提权，进一步渗透网站
- 传播蠕虫


产生原因：
1.网页中没有过滤字符的程序,被插入到网页中了




##xss分类
1.反射型跨站脚本
将恶意脚本附加到url地址的参数中
2.持久性跨站脚本
渗透，挂马，钓鱼等
跨站蠕虫


实列测试
http://xss.fbisb.com/


##xss构造剖析
xss  filtter--基于黑白名单
过滤敏感字符
但是可以用空格和tab等绕过
对标签值进行转义



事件:
1.用户接口
2.逻辑
3.变化


用注释字符绕过
/**/


shellcode
exploit
poc

基于script标签动态远程调用
或者运用基于DOM的方法创建和插入节点

xss downloader
xmlhttp


##测试和工具剖析
1.Firebug
动态修改html代码，搜索dom结构，监视网络请求和响应