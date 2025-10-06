# mihomo-config
自用 Mihomo 配置   
底版来自[@JohnsonRan](https://github.com/JohnsonRan)    
增添部分流媒体,加密货币,cloudflare,tmdb分组,tracker修改为自维护地址,emby修改为自维护地址,dmm分流默认强制走jp节点.  
默认fakeip,友情建议有qb,pt需求的还是redir-host，fakeip的话就建议兜底规则直连要么流量有很大跑飞可能.   
指着geoip还是不够,并且很多站盒子都是欧洲ip,如果用fakeip用geoip+兜底直连,可能qb流量会有偷跑.  
如果有pt需求内网有qb,redir-host,tracker直连,仅常用端口,基本作为主路由生产力没啥太大问题.  
把cf加进来主要是因为开了嗅探域名基本可以抓到比较精准的cf泛拨ip,会匹到cf分流,如果你的地区可以直连cf那cf分流直连可以帮你节省一部分机场流量尤其是某些不可说站点视频.
# 哪里没照顾到或者有什么玄学问题issues就行
