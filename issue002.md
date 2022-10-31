# Week 44 Of 2022

1. [黑客通过BGP劫持获利 @spin6lock](https://www.solidot.org/story?sid=72867)

黑客通过小型运营商发起BGP广播，劫持了特定的地址段，然后申请对应子域名的SSL证书，以此解密网站的用户数据并获利。BGP协议引起的错误都是比较严重的网络事故，2021年Facebook的宕机事件就是一起BGP引发的事故，参考[维基百科](https://zh.wikipedia.org/zh-cn/%E8%BE%B9%E7%95%8C%E7%BD%91%E5%85%B3%E5%8D%8F%E8%AE%AE)

2. [B 站重大线上事故 @wujiyu115](https://mp.weixin.qq.com/s/nGtC5lBX_Iaj57HIdXq3Qg)
     [OpenResty XRay 分析和解决 B 站重大线上事故](https://blog.openresty.com.cn/cn/bilibili-xray-incident/)
 B站7.13号重大事故,所谓千里之堤，溃于蚁穴,最后查出罪魁祸首竟然是有个函数对输入参数没有做类型校验导致死循环,链接2是openresty方对事故分析的视角
