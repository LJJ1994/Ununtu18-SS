## 1. 在Centos7上构建属于你自己的Shadowsocks服务
首先你需要购买一台vps服务器，网上有很多vps厂商，比如vultr，virmatch, 搬瓦工等
1. vultr
  价格还可以，可以无限创建销毁服务器，如果服务器IP被墙的话，最低一个月2.5美金，只提供ipv6, 建议购买5美金的，线路走传统163线路，一般我会选择硅谷地区。
  
2. virmatch
  价格非常便宜，最低1.5美金，也就是不到10RMB，而且带宽大，有1GB，速率有1GB，线路也是走163线路。

3. 搬瓦工
  知名的代理服务器提供商，优点是速度快，稳定，走CN2 GIA线路，目前最好的线路，没有之一，即使是高峰也是稳如狗。价格只有年付，49.9美金。
  
  总结，如果只是日常Google搜索，上推特，telegram，看视频要求不高的话，推荐选1, 2; 如果土豪，想稳定，要求速度的话，推荐选搬瓦工。搬瓦工还提供了自建的机场-Just my socks，只需要付费，会提供4个shadowsocks节点，并且节点被封会自动更换IP，如果不想折腾，推荐选这个。
 
 ### 以上可以自行搜索并购买服务器，选择vps关键词，不要选host之类的，在此不再赘述。
 
 ## 2. 下面以Virmatch为例，带领大家手把手建立shadowsocks服务。在此先通过Xshell连接你的远程服务器。
  ### 以下是virmatch控制面板提供的信息，其中ip是地址，用户名为root, 密码为 Root/Admin Password
  https://github.com/LJJ1994/shadowsocks_service/raw/master/images/test04.png
