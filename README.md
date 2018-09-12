# TimeSeed/BlockChat/BlockTalk/TimeBubble
基于 Nervos的社交相关应用(基于ReactNative & AppChain)

UI:

（1）好友列表（显示所有的，允许添加好友）

（2）朋友圈--显示所有好友的日记（自己的返回所有，其他人的就最多10条，拿到数据后进行排序）

（3）日记列表（显示自己的记录 以及 显示自己的胶囊（上面会附带发芽时间））

（4）发现：当日所有的发芽种子（非当日直接就遗弃掉）（自己的好友会排在前面，其他的会进行权重排行，允许点赞）

智能合约：

（1）每个用户分配账号

（2）获取本人所有消息列表接口（添加消息接口，删除消息接口）【消息排序规则：未解锁的--依据创建时间倒序。解锁的--依据解锁时间】

（3）获取本人所有好友列表接口（添加好友接口，删除好友接口，获取好友列表接口）【好友排序规则：根据name来排序】【好友添加上限是100】

（4）获取好友的最近10条消息接口（好友消息点赞接口，每人一票）

（5）获取进入解锁的胶囊列表接口（胶囊点赞接口）【排序依据好友，以及点赞量进行排序】

（6）同步时间设置为 30分钟

开发文档
AppChain文档：https://docs.nervos.org/nervos-appchain-docs/#/intro
Nervos白皮书：https://github.com/NervosFoundation/binary/tree/master/whitepaper
Nervos成都社群介绍
Nervos是一个区块链的基础设施。 https://docs.nervos.org/

我们Nervos成都社群第一批是定向邀请，定向邀请的要求是：对nervos感兴趣的开发者，我们能够一起提升对nervos的认知。

欢迎新朋友加入社群，需要您填写调查表（5分钟以内可以完成）：https://www.wenjuan.com/s/nQJv2y/ 稍后我们会邀请您入群。


