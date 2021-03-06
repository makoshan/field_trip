# Field Trip

## 介绍

项目名字来自于 Niantic 在 2012 年推出的一款地理分享应用 Field Trip ，鼓励玩家探索世界，结交新的朋友，外出活动身体，玩家可以透过 GPS 定位来探索周围各式各样独特的事物或隐藏的场所，Niantic 把真实的世界地图变成了游戏地图，陆续推出的《Ingress》、《Pokémon GO》与《哈利波特：巫师联盟》。

与此同时，人类社会正在经历一场数字化的进程，我们可以通过互联网完成越来越多的事情，衣食住行，也越来越离不开手机。但值得思考，我们是否深陷数字世界的乌托邦，听 IPN 旗下历史播客节目《壁下观》，他们提到了[纸上读，壁下观](https://www.douban.com/note/681014890/)，数字虚拟世界带给我们方便的同时，也不能忘记真实世界的感受 。

经历了这次新冠疫情，后知后觉的发现，自己竟然可以在家里待两个月不出门，可以在电脑旁坐一天，不同于我工作过两年的城市深圳，对于杭州我并没有任何地方感的记忆，本项目是我个人杭州物理世界的探索，也希望可以帮助大家与其周围社区和物理世界建立连接，了解你的城市附近有趣的地方，项目第一阶段专注于杭州。


## 项目目前进展

杭州城市探索地图
- 探索符合本地文化和充满地方感的地点: 景点、书店、餐厅、咖啡馆
- 地图预览：https://mako.bitcron.com/ingress


## 贡献

欢迎发 pull request 添加你去过的可以传递本地感的地方。获取网络速度和经纬度，然后添加到相应的 [geoJSON](http://geojson.org/geojson-spec.html) 中。如果没有你所在的城市，请新建一个 geoJSON 文件。格式请参见 [hangzhou.geojson](hangzhou.geojson)。

## 颜色标记

咖啡馆： "marker-color": "#F3AE1A","marker-symbol": "cafe"
书店： "marker-color": "#50C240","marker-symbol": "library"
景点： "marker-color": "#ce5c4e","marker-symbol": "triangle"

### 获取经纬度
[https://tool.lu/coordinate](https://tool.lu/coordinate/)，地图选择位置后，选择 WGS84 坐标系


### 特别感谢
本项目使用 [awesome-cn-cafe](https://github.com/ElaWorkshop/awesome-cn-cafe) 相关开源内容

## 相关链接
- [你从未认识你的城市](https://sspai.com/post/31152)
- [什么是Geocaching?](https://mako.bitcron.com/post/game/shi-yao-shi-di-li-xun-bao)
- [城市探索 App Mars](http://www.yohomars.com/)
