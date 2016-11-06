---
title: 一个Java程序员眼中的Mac OS（系列一：总纲领）
date: 2016-11-05 17:13:59
description: "站在开发者角度来谈Mac设备和Mac OS 。认真生活的非果粉用户。"
categories: [Mac]
tags: [Mac]
---


<!-- more -->


- ![一个Java程序员眼中的Mac OS](http://img.youmeek.com/2016/Mac-introduction.jpg)



## 系列教程总结


- 本系列会有 6 大篇，N 多小篇，6 大篇分别对应的是：
    - Mac 系统细节设置
    - Mac 常用快捷键说明
    - Mac 常用软件推荐
    - Mac 包管理和终端的使用
    - Java 开发者常见配置
    - Mac 外接设备推荐

------------

- 我喜欢纲领性的文章，不喜欢一篇里面太长。
- 在 6 大篇里面会是类似提纲一样的东西，里面布满标题和链接，跳转到我新开通的简书小号中，简书里面有对应标题讲解的详细内容。
- 我个人觉得这样学起东西来更加系统和有规律，也方便别人查询。
- 本教程使用环境
    - 设备硬件：2015 款 Retina MacBook Pro，i7，16G，256G。
    - Mac OS：macOS Sierra，10.12.1

------------

- 我不是果粉，也不是软粉，也不是 Linux 粉，我只会站在效率上考虑问题，不计代价的考虑效率，所以对于此系列的相关文章沟通，我希望我们是建议在以一个效率为核心的基础上进行。
- 我目前生活中开发，主力机还是台式机的 Windows 系统，我这个屏幕分辨率大，CPU 强悍，内存足够，SSD + 机械容量够装，所以如果在家开发我会选择 Windows 系统，但是不排除以后我适应了 Mac OS 以后，专门装黑苹果使用。
- 如果专门写东西，出门，浏览网页等等非开发、非游戏事情我会选择 Retina MacBook Pro，它小巧，屏幕清晰，软件友好，我坐着用不会那么累。



## Mac OS 使用感受总结

- 我现在同时具备了三种类型的系统使用习惯：Windows、Mac、Linux，所以我想我现在多少有话语权来推荐这三个系统了。
- 为了更适应大众，更适应效率，对比这三个系统的前提是：不考虑钱和职业的情况下。
- 这三个系统里面没有所有方面都最好的，因为都是有侧重点和自己的定位的。
- Linux 是最简单划分的：Linux 最适合服务器部署，不适合桌面，所以只要你经常跟桌面打交道的都不建议。
- Windows 和 Mac 倾向于普通用户，适用于桌面用户，如果要从这两个里面挑一个推荐给大家的话，我会这样分情况。
    - 1.如果使用的对象是小孩，是他的第一台电脑的话，我会选择 Mac。里面英文软件多，屏幕好，最重要的是软件生态圈中有很多在维护的好软件和小软件，软件生态圈并不是完全依赖大公司或是苹果本身。
        - 在这里也强调下，苹果所维护的收费软件生态圈确实比 Windows 好很多，那些开发者能有收入，他们才会继续进行维护。而对于中国的使用者来讲，好的英文软件多了，会间接促进他学好英文，沟通外面世界。所以我也发现为什么那些很早以前玩 Mac 的，说自己是果粉的英文都还不错，我觉得这个是有一点作用的。
    - 2.如果被推荐的对方是成年人，那我又会细分为下面两种：
    - 2.1.如果这个成年人会愿意花时间学习，并且有英文的一些底子，不反对英文，那我会推荐 Mac，因为 Mac 有很多优秀的软件可以增加效率的，而这些很多都是英文软件，我后面都会来一一推荐，并且硬件设备也一直处于世界最前沿的。
    - 2.2.如果这个成年人不喜欢学习新东西，只是平时回家就是玩玩电脑游戏，看看视频聊聊天刷刷微博看看朋友圈什么的，我会推荐 Windows，Mac 在娱乐这条路上不是 Windows 的对手，微软有 XBOX 做后盾。


## Retina MacBook Pro 笔记本总结

- 优点：
    - 轻便，性能不差，待机长，适合出门。
    - 量测喇叭清澈，音乐人适合。
    - 视网膜的显示屏没什么可以挑剔。
    - 系统字体渲染确实很棒，很清晰
    - 触摸板好用，非常好用
    - 系统备份功能强大
    - 收费软件生态圈比 Windows 好很多，原因前面说了。
    - Unix 系统，对于懂 Linux 部署环境的 Java 开发者来讲是很友好。
    - 如果你是 iPhone 手机用户，同时有开启 iCloud 的话，那有些数据同步上也是很方便的，比如我常用的备忘录、提醒事项，同时手机使用的 WIFI 密码，笔记本也会自己记住等等这类细节。
    - 很多软件都没有中文版，对日常英文的回顾是有帮助的。
- 缺点：
    - 贵，真心贵
    - 在 Mac 下，那些国外软件反而都很好，反而是很多国内软件很糟糕，不管是有道词典、QQ、搜狗输入法、为知笔记、百度云盘等等，都做得比 Windows 差，很多设置、功能都去掉了。
    - 软件设置少你可以叫做简洁，但是我也可以叫做功能简单，有些人用不到这些设置，但是对于我这类喜欢设置很多习惯的人来讲，我不觉得这样是简洁。我不知道是不是苹果没给权限还是什么的，反正我是非常不满意的。


## Mac 机子购买建议

- 优先根据职业来划分情况：
    - 如果你是开发者、设计师、视频编辑、音乐编辑等 IT 相关职业者，那你的预算必须在 1W，必须选择 Retina MacBook Pro 系列，不然怕是扛不住你的日夜虐待的。
    - 如果你是非IT职业者，平时也生活所用，不会有太多资源的运作，那你的预算必须在 7K，你可以考虑入手 MacBook Air，这个平时使用的，而且待机又长，很适合出门轻度使用者。
- 作为开发者，如果你初期经费不够的，预算小于 1W，不建议你买 Mac 的任何产品，那些低于 1W 的 Mac 产品不会让你有多大的效率进步的，当然了，前提是你也确实对 Windows 也足够了解。
- 如果你经费在 1W 左右，那可以大胆尝试下 Retina MacBook Pro 不管是 2015 年款的还是最新的 2016 款。Mac OS 上其实也很多破解软件的，而且安装起来也很简单的，所以不会影响你工作效率。当然了，前提还是你要花时间去找资料学习下。
- 如果你已经进入一个比较好的后台开发状态，那我建议你手头有一台顶配的 Windows 台式机，一台 Retina MacBook Pro 笔记本。预计这需要花费 2W ~ 3W 左右，你可以分阶段来。
- 如果你非常着迷 Mac，那就一台顶配 Intel 台式机用来装黑苹果，一台 Retina MacBook Pro。

     
## 结束语

- 买 Mac 设备装双系统我觉得没必要，如果你就一台机，那我就只建议你专心用 Mac OS 或专心用 Windows，如果习惯 Windows，那就专心买 Dell XPS，Surface Book。
- 如果你打算认真从事开发行业，那就等手里有钱之后，按我刚刚说的，笔记本用 Retina MacBook Pro，台式机组装用 Windows 或 黑苹果。
- 下期预告：一个 Java 程序员眼中的 Mac OS（系列二：Mac OS 系统细节设置）