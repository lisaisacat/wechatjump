# wechatjump
微信跳一跳游戏辅助

本本源码主要来自知乎 xtutu 的分享，在此感谢。

在之前源码的基础上，做了以下优化：

增加了配置界面，更方便普通玩家使用。

增加了对更多分辨率的支持，目前支持 720x1280,1080x1920,5/5C/5S,6/6s,6P/6sP

开发环境

电脑：Windows 或 Mac

软件：Lua 编辑器、抓色器（可以在官网 http://www.touchsprite.com/tools 下载）

手机：触动精灵（iOS 或者安卓都可以）

工作原理

抓色器远程连接手机截图，找到坐标点和颜色值，作业部落上有使用教程。(https://www.zybuluo.com/miniknife/note/629913)。

通过 Lua 实现模拟点击

