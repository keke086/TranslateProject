Linux 大爆炸：一个内核，无数发行版
============================================================
[Print][1][Email][2]By Jonathan Terrasi  Apr 27, 2017 3:24 PM PT

![linus-torvalds](http://www.linuxinsider.com/article_images/story_graphics_xlarge/xl-2017-linus-torvalds-1.jpg)

即使你是 Linux 新人，或许你已经知道它不是一个单一的整体操作系统，而是一群项目。这个星座中不同的“星”组成了“发行版”。每个都提供了自己的 Linux 模式。

要欣赏这一系列发行版提供的多种选择，这有助于了解 Linux 如何开始并随后激增的。考虑到这一点，这里简要介绍一下 Linux 的历史。

### Linus Torvalds，内核构建者

大多数熟悉 Linux 的人都已经听说过它的创建者，Linus Torvalds （上图中的人）, 但是并不知道他最初为何创建它。在 1991 年，Torvalds 是一名在芬兰学习计算机的大学生。作为一个独立的个人项目，他希望为他的独特硬件创建一个类 Unix 内核。

“内核”是通过其固件和操作系统在硬件之间进行协调的操作系统的一部分。本质上，它是系统的核心。开发内核不是一个小工程，但是 Torvalds 渴望挑战，并且发现他自己有这个罕见的技能。

由于他刚接触内核，他希望得到其他人的投入来确保他在正确的轨道上，因此他通过在早期的互联网论坛 Usenet 发布他的内核代码并征求了老牌的老手的经验。贡献者涌入了。

在建立了一个检查论坛提交补丁以及选择性地集成它们的流程后，Torvalds 意识到他聚集了一个非正式的团队。在项目发展之后，它很快成为了一个有点正式的开发团队。

### Richard Stallman 的角色

虽然 Torvalds 以及他的团建创造了 Linux 内核，但是没有 Richard Stallman 的工作也不会有随后 Linux 众多发行版的传播，他在十年之前启动了一个自由软件运动。

受到许多核心 Unix 编程和系统程序缺乏透明度的阻挠，Stallman 决定自己编写，与任何想要它的人自由共享源代码，并且开放提交。他创造了许多核心项目的主体，并在 1983 年发布，统称为 “GNU 项目”。

没有它们，内核不会有那么多的使用。基于 Linux 操作系统的早期设计人员将 GNU 工具轻松地并入他们的项目中。

不同的团队开始出现 - 每个团队都有自己的计算功能和架构理念。它们结合了 Linux 内核、GNU 实用程序和他们自己的原始软件以及 Linux 操作系统的“发行”变体。

### 服务器发行版

每个发行版有它自己的设计逻辑和目的，但是要了解它们的细微差别，需要了解上游和下游开发人员之间的区别。“上游开发人员”负责实际创建项目并发布以供个人下载或将其包含在其他项目中。相比之下，“下游开发人员”或“软件包维护人员”是指每个发布上游程序的人员，并进行调整以适应下游项目的使用情况。

虽然大多数 Linux 发行版包含一些原始项目，但大部分发行版是“下游”的 Linux 内核、GNU 工具和庞大的用户程序生态系统。

许多发行通过优化特定使用场景来标记它们的特征。例如, 某些项目被设计作为服务器运行。为部署服务器而量身定制的发行版通常会避开上游项目中快速推出最新的功能, 而倾向于发布一个经过彻底测试的、基础的基本软件, 这些系统管理员可以依靠它来顺利运行。

针对服务器的开发团队经常很大，并且有富有经验的程序员可以为每个版本提供多年的支持。

### 桌面发行版

也有很多的发行版针对桌面用户。事实上，一些知名的发行版通过提供简单的安装以及直观的界面来与商业的操作系统竞争。这些发行版通常包含了大量的软件仓库，它包含了用户可以想到的每个软件，这样用户可以制作它们自己的系统。

由于可用性是关键，他们可能会投入部门大量的员工来创建一个签名、发行版特定的桌面，或调整现有的桌面以适应其设计理念。以用户为中心的发行版往往会加快下游开发时间表，有助于及时为用户提供新功能。

“滚动发布”项目 - 桌面发行版的子集 - 被设计成紧跟潮流。滚动发布项目的包维护人员在完成调整后会分别发布每个上游程序的新版本，而不是等待所需的上游程序达到某一特定的开发点，然后将其集成到单个版本中，。

这种方法的一个优点是安全性，因为关键补丁将比非滚动发行版更快。另一个好处是新功能立即可用，不然用户将不得不等待。滚动发布的缺点是需要更多的人工干预和仔细维护，因为某些升级可能会与其他升级相冲突从而破坏系统。

### 嵌入式系统

另外一个 Linux 发行版类别是“嵌入式系统”，它被极限地裁剪（相对与服务器和桌面发行版）来适应特定的使用情况。

我们经常忘记任何连接到因特网的东西，或者比一个简单的计算器复杂的东西，都是计算机，计算机需要操作系统。因为 Linux 是自由的并且高度模块化，它通常是硬件厂商的选择。


在大多数情况下，如果你看见一台智能电视、一台连接互联网的照相机、甚至是一辆车，你看到的都是 Linux 设备。特别是每部不是 iPhone 的智能手机运行着不同的嵌入式 Linux。

### Linux Live

最后，有一些 Linux 发行版并不着永久性地安装在计算机中，而是驻留在 USB 记忆棒上，并允许其他计算机启动它们，而无需计算机硬盘。

这些 “live” 系统可以被优化来执行一些任务。从修复损坏的系统到进行安全评估到高度安全浏览因特网。

由于这些 live Linux 发行版通常针对解决特定的问题，因此它们通常包含特定的工具，像磁盘分析和恢复程序、网络监控程序和加密工具。它们还占用很小的空间，因此它们可以快速启动。

### 你如何选择？

这绝不是 Linux 发行版类型的全面列表，但那是它应该让你了解一个范围以及 Linux 生态系统的多样化了。

在每个类别下都有许多选择，因此你会如何选择一个最能符合你需求的版本呢？

一种方式是试验。在 Linux 社区中，来回尝试不同的发行版，或者用户根据他们的需求在不同的机器上运行不同的发行版很常见。

在将来的文章中，我会展示每种类型发行版的几个例子，以便你可以自己尝试，并开始探索最喜欢的发行版的旅程。

--------------------------------------------------------------------------------

作者简介：

自 2017 年以来 Jonathan Terrasi 一直是 ECT 新闻网的专栏作家。他的主要兴趣是计算机安全（特别是 Linux 桌面），加密和分析政治和时事。他是全职自由作家和音乐家。他的背景包括在芝加哥委员会发表的保卫人权法案文章中提供技术评论和分析。

------

via: http://www.linuxinsider.com/story/84489.html?rss=1

作者：[ Jonathan Terrasi ][a]
译者：[geekpi](https://github.com/geekpi)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://www.linuxinsider.com/story/84489.html?rss=1#searchbyline
[1]:http://www.linuxinsider.com/story/84489.html?rss=1#
[2]:http://www.linuxinsider.com/perl/mailit/?id=84489