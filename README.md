# DiscordSay
## 简单的Discord水群机器人
discord_link:discord的频道。比如：discord.gg/xxxx

token:这个很重要，他是一个discord账户登陆的token，简单理解为token就是钱包的私钥，非常重要，不要泄漏给任何人，当然它有时效的，过几天就失效了

这个值怎么获取呢？

就是打开discord的网页，打开登陆界面，然后F12打开调试界面。

然后点击登陆，在调试界面的Application中，输入token，然后这个value值就是token



channel_id:频道的id，这个就是discord群组里你想要划水的频道id，怎么拿到呢～

就是在discord设置里把开发者模式打开～



然后在频道右击，复制频道id即可



time_interval:聊天的时间间隔，比如60就是每60秒发送一次

剩下的汉字就是每次要发送的话，目前策略是循环顺序发送，1发完 发2 2发完 发3.。。

里面现在有50句话，稳妥的老铁可以放个100多句话，肝～～～
