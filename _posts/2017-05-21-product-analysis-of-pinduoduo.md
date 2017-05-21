---
layout: post
title: "【008】『拼多多』产品体验报告"
comments: true
description: "『拼多多』产品体验报告"
keywords: "拼多多,产品分析"
---

### 1 市场现状

根据2016年中国互联网络发展统计报告显示，截止到2016年12月，我国网络购物用户规模达到4.67亿，占网民比例为63.8%，较2015年底增长12.9%，其中手机网络购物用户规模达到4.41亿，占手机网民的63.4%，年增长率为29.8%。网络购物市场已经进入成熟期。

![电商市场规模](http://img.blog.csdn.net/20170521113037476?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
 
『拼多多』成立于2015年9月，将娱乐社交融入电商运营，通过“**社交+电商**”的模式进入电商红海，经过不到两年的时间做到用户量破亿，成为继淘宝、京东之后的第三大电商小巨头。截止2017年5月18日，拼多多在IOS免费总榜排名12，购物类榜单排名第2（前面两名分别是淘宝、京东）。

![排名趋势](http://img.blog.csdn.net/20170521113546516?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
2017年1-2月，购物类app排名集体下降，可能与春节放假有关。

百度指数：整体搜索指数呈不断上升趋势，移动端和整体趋势相同。

![拼多多-百度指数-总体趋势](http://img.blog.csdn.net/20170521113725611?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
![拼多多-百度指数-移动端](http://img.blog.csdn.net/20170521113736721?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

2016年9-11月，拼多多百度搜索指数有几次出现陡增现象，查了一下相关活动和新闻，猜想可能有以下几种原因：

- 双11活动；
- 2016年9月14日，拼好货和拼多多合并，用户量累加；
- 2016年7月20日，获得了高榕资本、新天域资本、腾讯等机构1.1亿美元的B轮投资，入驻商家增多，优惠活动增多，优惠力度增大，拉动用户量。

根据ASO100统计，从2016.8.1到2017.5.18，拼多多在苹果市场下载量预估总计：2738.7万；截止到5.18，在安卓市场下载量达2.58亿，同百度搜索指数上升趋势相同。

IOS下载量:

![IOS](http://img.blog.csdn.net/20170521114206551?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
Android市场下载量：

![Android](http://img.blog.csdn.net/20170521114216962?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


---
### 2 产品需求
#### 2.1 产品定位
slogan：多实惠，多乐趣。
定位：电商+社交
用户通过发起和朋友，家人，邻居等的拼团，以更低的价格，拼团购买商品。旨在凝聚更多人的力量，用更低的价格买到更好的东西，体会更多的实惠和乐趣。

#### 2.2 用户画像

地域分布：

![地域分布](http://img.blog.csdn.net/20170521114617515?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

用户主要分布在沿海发达城市。

年龄分布：

![年龄分布](http://img.blog.csdn.net/20170521114728501?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

用户年龄主要集中在19~45岁之间。

消费偏好：

![消费偏好](http://img.blog.csdn.net/20170521114842022?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

用户主要偏好大众品牌和时尚品牌。

性别分布：

![性别分布](http://img.blog.csdn.net/20170521114944051?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

男女比例大概2:3，女性用户偏多。

综上，拼多多的目标用户群体为：

 1. 19~25岁的在校大学生，他们没有经济来源，乐于网上购物；
 2. 工作年龄不长的的上班一族，他们面临买房买车的压力，比较关注商品的价格，而非品质；
 3. 精打细算，爱贪小便宜的中年大妈们，她们追求各种方式获得商品的更低价格。

####  2.3 用户需求 
追求商品更低价格，并乐于和身边的人分享交流

---
### 3 产品体验
#### 3.1 视觉体验
logo：红色为底，主体形状为桃心；桃心外围是各种商品，中间为app名称简称“拼”，突出产品定位的电商购物产品。app内主体颜色红白相间，主题突出红色，和logo配色一致，视觉上整体比较和谐，体验较舒适。

短评：5tab布局，下边tab栏为白色，点击对应tab，该tab和标题栏颜色变为红色，但中间3个tab对应标题栏为白色，给人视觉上很突兀的感觉，建议上方标题栏统一为红色背景。

```
为什么电商类产品logo偏爱红色？
红色：代表冒险，给人心跳加快、马上行动的感觉，适用于清仓大甩卖这种冲动消费的场景。
```

![视觉体验](http://img.blog.csdn.net/20170521120856266?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)



#### 3.2 产品功能

![产品功能结构图](http://img.blog.csdn.net/20170521121434831?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

#### 3.3 特色功能

•	拼团
站在开团者的角度，在购物过程中有交流、互动的需求，分享给朋友、熟人，一方面可以对该商品进行筛选和甄别，另一方面双方都可以获得优惠的产品价格。
站在被分享者的角度，如果这件商品拼团后确实非常优惠，可以和朋友一起买，还顺便帮朋友一把。

![拼团](http://img.blog.csdn.net/20170521131949003?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

•	海淘
海淘是拼多多主打的一项业务，在app菜单最中间的位置，特点是“正品保障，包税包邮，极速发货”，选择海淘作为核心功能可能与网易考拉、丰趣海淘等多家知名海淘品牌的入驻有关，除了价格上的优势外，海淘产品的质量有保障。

![海淘](http://img.blog.csdn.net/20170521132900386?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

•	亮点
拼多多有一个特色：每次有人开团，在app界面左上角的位置都会显示“xxx 1秒前开团了”的通知，这样实时的显示开团信息可以营造团购气氛，增加买家剁手的欲望。

![亮点](http://img.blog.csdn.net/20170521133425369?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

#### 3.4 产品逻辑

![产品逻辑](http://img.blog.csdn.net/20170521135236424?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

拼多多的购物逻辑主要围绕拼团模式设计，用户可以选择一件开团也可以单独购买，单独购买优惠力度肯定没有拼团大，价格上的对比鼓励用户选择拼团模式。下单成功以后可以将拼团信息发布到你的朋友圈、微博等社交圈子，也可以由app内有同样购买需求的陌生用户组团。一旦达到拼团人数的条件，就被认定为拼团成功，各个买家将获得优惠的拼团价格，且商品将分别发货。若无法满足拼团要求，则拼团失败，付款金额将返回给用户。


---
### 4 盈利模式
和其他电商app一样，拼多多的盈利途径主要有赚佣金、赚差价、赚平台上商家的广告费等，商家入驻缴纳的保障金也是很大一笔现金流。

---
### 5 产品建议
本人选取ASO100上统计的典型用户评论20条，好评和差评各10条进行分析如下。

![评论](http://img.blog.csdn.net/20170521140219902?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

好评主要集中在**价格便宜、性价比高，种类齐全，产品体验好，以及时尚、海淘产品好**等；

差评主要集中在**产品质量，运营客服和物流上**，另外在水果拼团上，主要围绕水果保质期、虚假发货等网络上出现一片骂声。

结合用户反馈和自己的产品体验，对拼多多有如下建议：

1.	进行买家、卖家互评机制，筛选出优质店铺和购物达人；
2.	不要只追求低价，更要注重品质，有品质才能走得更远；
3.	完全依赖于微信等其他社交圈，无法形成商业闭环，可以试着构建自己的用户社区（如淘宝的微淘、问大家，京东的寻Me等）；
4.	拼团只适用于小金额商品，对于电子设备、家电器材等大金额产品需要转换拼团思路。

最后再多说几句，对商品质量的把控是任何一个电商平台核心问题，随着经济的发展人们会越来越关注产品的质量而不只是价格。其次，建立完整的互评体系，因为用户购物时对商店的好评率还是很看重的，虽然当下存在者店铺刷单、刷好评的现象，但是这不应该成为去除这个功能的原因，可以通过其他办法解决以上刷单等问题。最后是要完善平台的运营、客服、物流体系，切忌发布虚假信息来诱导用户来短暂提升下载量。

拼多多这个后起之秀，凭借“社交+电商”的模式在电商的红海杀出一条路，到目前为止取得了不错的成果，随着腾讯的投资加持，拼多多如何更好利用社交流量实现持续的盈利，让我们拭目以待。

---
数据来源：
1.2016年中国互联网络发展统计报告

2.ASO100

3.百度指数

4.移动观象台
