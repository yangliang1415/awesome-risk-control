````
v1.0: update@20181202

TODO
风险点梳理：图
风控架构：图

风控算法相关梳理
风控资料梳理
````



# 一、所谓风控

所谓风控，即 `风险` `控制`

`风险`  特指互联网产品中存在的风险点。例如账户风险(卖家，商户)，交易风险(刷单、盗刷、套现)；UGC风险等

`控制` 即是要 `识别`   `预防`  ` 控制` 这些风险。识别强烈依赖于 `数据特征` 和 `规则模型`

TODO：风险点梳理，利益点和风控诉求

# 二、如何风控

如上所说，控制依赖于数据特征和规则模型。

## 数据特征

一般针对需要风控介入的场景，称每次场景下的行为为一个事件，例如称一个新用户注册为一个注册事件，一次下单为交易事件，一次支付行为为支付事件等等。

上面描述的事件，称为基本`事件数据`。

针对时间数据，可能做多种维度的统计和分析得到处理后的数据，称为 `特征数据` 。



## 规则模型

TODO：规则引擎；算法模型

## 一般架构

TODO：架构大图，系统关系

风控接入

规则引擎

事件特征中心

处罚中心

审核中心

案例



## 行业风控参考

小米：https://toutiao.io/posts/c355w5/preview

饿了么：https://blog.csdn.net/gitchat/article/details/78086327

美团：美团博客上的后来被删除，估计是太敏感了。不过网上应该都能搜到。 待补充

携程：https://mp.weixin.qq.com/s/muufqznNNVidPgamlcurCQ

TODO：资料搬到本地，防止链接失效等

# 三、风控圈子

`同盾` `张新波` http://xinbo.me/

`美团` `唐义哲` http://typd.github.io/pages/about-me.ch/

`唯品会` `WalterInSH`  https://github.com/WalterInSH/risk-management-note



相关会议

SACC 2016 互联网安全和风控体系 会议分享(京东、爱奇艺、美团等)：http://safe.it168.com/a2016/1028/3000/000003000971_all.shtml



# 四、风控相关招聘

TODO: 分为架构和算法，总结招聘要求所需技能点

拼多多：https://www.lagou.com/jobs/3458578.html?source=position_rec&i=position_rec-2



# 五、参考

支付宝如何识别骗子：https://www.zhihu.com/question/20669015