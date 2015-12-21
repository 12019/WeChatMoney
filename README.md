# WeChatMoney
业余时间写的微信抢红包插件

项目工程介绍
fakeapp 模拟微信红包流程app 点击按钮后会发出notification，点击notification可以进入领取红包界面戳一下即可拆红包。

fakemoneyservice 模拟抢微信红包流程app后台开的服务。

装上以上两者后，再打开fakemoneyservice后，就会自动触发抢红包流程。

通过这两个工程，旨在让大家快速熟悉抢红包流程和AccessibilityService基本使用方法


wechatmoney 加强版本功能

1.能监听notification变化

2.自动解锁

个人红包® 共有5种状态

1.信息提醒状态 在通知栏中出现的状态。即有一条红包的信息来了～

2.初始状态 信息流中红包最早发出去时的状态，既没有点开，也没有领取的“初始状态”。

3.拆红包状态 信息流中红包点击一下进入的状态，这个状态会出现一个大大的“拆红包”字样的界面

4.领取红包状态 点击拆红包之后的状态 这个状态会进入到红包详情页面

5.终结状态 红包已领完，返回到信息流页面（暂时没用）

1->2 点击消息

2->3 点击初始状态的红包

3->4 点击拆红包
R
4->5 点击back键

5->4 点击终结状态的红包(未处理)



###安装fakeapp&fakemoneyservice的结果

 ![演示demo](money.gif)
 
 
###原始安装fakeapp的结果

 ![演示demo](money1.gif)
 

###红包演示视频

 ![演示demo](money2.gif)





