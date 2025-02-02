# [cs-ruankao](https://www.ruankao.org.cn) 👋

+++

> **最近更新（20211103）**：考试已经取消，重新制定其他学习计划，宣布此项目进入冻结状态吧，我会把项目 Archived。后面也许会继续收集相关资料，也许不会，但我会关注其他地区的考试以及题目。如果还有机会参加考试，那么我将继续更新，一切随缘吧。这里分享的资料一直都在，有需要的小伙伴各取所需，我们后会有期。

+++

个人备考计算机软考仓库，主要以高级的系统架构师科目为主，其他为辅。内容主要由个人的复习经历以及资源收集组成，不定时更新。

本仓库中的文件大多来源于网络以及 xxlllq 群主的分享，我只是根据个人的需求做了整理，如有侵权，请联系我删除。

关于跨步软考的资源，大家可以选择性下载，其他资源大家则根据自己的需求进行下载。后面有好的资源也会一并分享到这里，欢迎大家一起维护。

## 自说自话

- 2021-11-03：今天收到考试中心的电话和短信，考试取消，随即把所有复习资料丢到了一边，拿出以前的资料继续复习（先玩几天吧）。
- 2021-10-29：这边考试还没有任何消息，估计也是在看疫情情况，我已经无所谓了，考也行，不考也罢，反正我的复习一直在继续。

- 2021-10-26：目前还无法确定考试能否如期举行或者停考，但复习还应该继续，虽然之前有短暂的瓶颈期，浪费了一周左右的时间，但好在一直没有放弃，希望各位小伙伴也要一直加油，这几天主要攻克一下论文。
- 2021-10-15：真题已经刷完一遍，手写了部分案例和论文，并且开始疯狂的背诵笔记、真题案例和论文，然后再刷一遍真题。
- 2021-10-03：重新评估时间和复习情况。
- 2021-09-15：大家一定要计划好时间，最近工作比较麻烦，所以工作中很难静下心来学习，回到家也懒得学习，这么下去的话，时间肯定是不够的，希望大家可以继续坚持一段时间。

## 2021 年论文预测

> 自己预测了几个论文主题，根据历年考试情况进行预测的，看看就好，别当真，后面 21 年的题目再出来看看是否猜对了。

- 系统建模，如建模方法，视图建模
- 软件可靠性，相关技术，分析方法
- 设计模式，三种类型及其所包含模式的定义
- 架构设计，结合时下前沿技术进行架构设计，比如 DDD（瞎猜的）

## 考试相关


### 关于考试时间及科目次数

报名一般在 8 月到 9 月份之间，费用 100-200 不等，不同地区价格不同，考试是在 11 月 6 日左右。中级所有科目都是一年两次，高级的信息系统项目管理师是一年两次，系统架构设计师和网络规划师是每年的下半年考试，系统分析师和系统规划与管理师是每年的上半年考试。

这里贴一下官方的时间安排截图。

![](https://github.com/i0Ek3/cs-ruankao/blob/master/images/schedule.jpg)

上午的选择题是 75 道，两个半小时；案例分析师五选三，一个半小时，其中第一道必选；论文的话是四选一，两小时。

> ~~个人目测了一下，案例的时间可能有点紧，我自己算是手写速度算快的（不能保证字迹工整），但依然没有什么空闲时间写案列，所以案例一定要好好准备。论文其实还好，我完全手抄大概需要 1 小时 20 分，自己准备好模板，稍微构思下，1 小时 40 分钟应该可以拿下论文。~~
>
> 做了几套真题后，重新来评估一下。上午的题应该没有问题，慢一点 30 分钟也能完成 75 道题目，应该和我刷题有关，到考场应该会放慢速度。案例的话，如果你对知识点了解的还不错，那么写起来应该差不多，时间刚好够用（以我自己的手速）。但是如果你对知识点不甚了解，那就比较尴尬了。所以，大家还是好好背真题的案例和相关知识点吧，平常自己也多抄写练下手速。论文的话肯定要提前准备模板了，目前自己写时间可能有些紧，如果直接抄写别人现成的，大概还有 30 分钟的剩余时间。前提是四道题目中有你熟悉的点，如果都不熟悉，那就只能生搬硬套了，此时就突显出提前准备模板的重要性了，因为如果你不会或者跑题了，但是摘要、开头和结尾写的还不错，我猜情况会有扭转吧（纯属个人猜测）。所以大家的手速一定要跟上，不然写论文很吃亏。

### 具体考试内容

这里贴一下系统架构设计师的具体考试内容，截取自王勇老师的视频。

![](https://github.com/i0Ek3/cs-ruankao/blob/master/images/content.jpg)


### 关于考证的必要性

之前在学校考过 2 次中级，都没有考过，最后也没觉着多有用，也就放弃了。到单位上班后才发觉，软考证书真的很有用，正如我在[这里](https://github.com/i0Ek3/work-and-life-in-system#13-%E6%8F%90%E5%89%8D%E5%87%86%E5%A4%87)和[这里](https://github.com/i0Ek3/work-and-life-in-system#43-%E8%AF%84%E5%AE%9A%E4%B8%8E%E8%81%98%E7%94%A8)提到的，中级和高级分别对应到了中级职称和高级职称，还是很有意义的。


### 关于考哪个级别

原本是打算先考中级的软件设计师，这个的把握要大很多，考过了就可以先聘中级。但是后来打听了一下，我们这边只要有高级证书，也是可以聘中级的。所以既然要考，不如多花点时间好好准备一下突击高级的系统架构师，万一中级不过也是很尴尬的，况且个人对架构设计也很感兴趣，所以还是想着碰碰运气的同时也好好准备一番，争取一次通过。


## 个人笔记及经历

2021.8.20 本地开启报名，报名费用 224。一直到 9 月 15 日，官网依然没有编排考场信息（倒是这个也不用关注，大家专心复习就好了）。

### 个人复习方法

- 先快速过了一遍希赛的第四版教材，耗时一周
    - 其他的教材可不看，有了大致了解后主要还是攻破真题中的知识点
- 看视频，搞懂重、难点知识点
    - 目前只看了一部分，针对不懂得再看，会的就不看了，其实后面也懒得看视频了，大概只看了 80% 的视频，后面实在没时间了
- 关注案例和论文，看真题、其他人的模板以及极客时间的架构课程
    - 此时只是了解即可，回想自己过往做过和参与过的项目，一定手抄模拟一下考试的感觉，看看自己的手速等
    - 其实还是要提前准备的，目前来看时间略有仓促，有点赶（虽然我还要保证每天都要看 2 集良医😂）
- 专项训练
    - 搞清楚每一章的考试内容，出题风格是怎样的
    - 目前已经刷了一遍专项，第二遍也快结束了，重点针对错题和没记住的知识点
    - 接下来对专项训练中拿不定的题目继续攻克，再做上几遍，等做的差不多的时候开始做真题（其实专项的册子就是真题组成的，专项差不多的时候，真题也就没啥问题了）。与此同时，论文和案例开始手写（前提是你掌握了相关知识点，并且自己手写了一些模板，有自己的套路，一定要提前准备。我估摸着，现在的时间可能有点紧了）
- 真题训练
    - 有时间和精力的多做几遍，其实此时主要是案例和论文了，综合应该是差不多了，剩下的背背知识点吧，卡点，不懂的搞懂，形成个人习惯，保证做题速度和正确率
    - 根据目前做题的情况来看，以及还剩 30 天左右的时间，应该重点搞真题的案例和论文，有条件和时间的情况下，可以整体多过几遍，但是恐怕没有时间了，所以大家一定要规划好时间。如果我没有在国庆七天专心复习，怕是结果更加难堪
- 复盘总结
    - 路上或者平常不忙的时候，可以拿出手机用 app 来刷题巩固（路上刷题看来是不可能的了😂）
    - 错题回顾，保持案例和论文的手感
    - 一定要有好心态，坚持


### 一些建议

如果考高级的话，可以先报名一个比较简单的项目，比如信息系统项目管理师或者系统规划与管理师。相反，系统架构设计师和系统分析师比较难考，根据往年的通过比例，系统分析师的通过人数简直是少的让人”发指“，系统架构设计师则相对好一些。本人报考的原因仅仅是因为感兴趣和收集到了相关的资料，并没有做全面的考虑。所以，这次无论如何都会全力以赴。

相关讨论可参考[这里](https://www.zhihu.com/question/307034088)，值得说明的是，所有观点都是因人而异的，所以最后的结果还是在你自己。

知乎上有一网友分享了自己的[考试经历](https://zhuanlan.zhihu.com/p/340310138)和自己写的[论文](https://blog.csdn.net/sinat_31152963/category_10672942.html)，个人看来还是不错的，而且这位网友的分数较高，值得学习与借鉴。我对该网友的经历和论文做了整理，特制作了 pdf 版本和 word 版本方便打印学习，有需要的小伙伴自行安利。

另外，在整理资料的过程中，发觉了某位网友关于论文写作的[分享](https://mp.weixin.qq.com/s/E97YA-VktIoEmOCwZ2EUqg)，还是非常值得参考借鉴的，大家可以多读几遍了解一下。另外他的公众号里也分享了很多关于软考的资源，大家可以关注领取，作为补充。

## 相关资源

> 这里做一个声明，因为以下资源均来自网络，根据原作的要求（或者根据我个人的原则），我会对资源进行不定期调整，请大家不要将这些资源进行二次售卖，尽量去维护一个比较和谐的分享环境。若因私自进行售卖这些资源而导致的法律纠纷，本人不会对此负责，大家且行且珍惜。


### 希赛资源

这里提供一个希赛官方的[真题集锦](https://www.educity.cn/rk/zhenti/jiagou/)，有网页版，也可以下载 pdf 版本。不过只有 09-18 年的（页面里 20 年的下载下来还是 18 年的，19 年的未列出），大家可以自行下载打印，也可以用我整理的（已经放在真题文件夹），或者直接运行我写的下载脚本（仅支持 Unix/Linux 系统）。

`$ ./download.sh`


### 公开真题吧

这里在提供一个[真题链接](https://www.gkzenti.cn/paper?cls=软考&province=高级_系统架构设计师)，仅仅是网页版的，排版质量还不错，可以参考。希赛资源里 18 年的案例和 17 的综合排版有些问题，可以用这个来看，也是只有 09-18 年的，后面有时间可以写个脚本抓取网页并转存为 pdf，不过暂且不需要了，嘿嘿。


### 跨步资源

- 信息系统项目管理师 `百度网盘：链接: https://pan.baidu.com/s/1PmVFPXVMkG1NK5j_Fgqjog 密码:wjmb`
- 系统分析师 `百度网盘：链接: https://pan.baidu.com/s/1kD2uBch39YMPrlv2PztwPg 密码:vytf`
- 系统架构设计师 `百度网盘：链接: https://pan.baidu.com/s/19LEiYbYIwnhBqheOiemOzg 密码:ghjh`
- 网络规划设计师 `百度网盘：链接: https://pan.baidu.com/s/1zSioM8NTtVgxrJ6h76N_ZQ 密码:43o2`
- 系统规划与管理师 `百度网盘：链接: https://pan.baidu.com/s/1L-A2-P3ZOsFYgrYs6c5nfw 密码:1n0u`
- 软件设计师 `百度网盘：链接: https://pan.baidu.com/s/1nM4J-MIj2WbQOCSiALLfqg 密码:mtj2` 

> ps: 跨步软考资源已经永久停更，9 月 5 日查看，跨步网站已经无法正常使用，上面链接可用。


### GitHub 网友整理资源

这里我只放一些我觉着还不错的 GitHub 链接，有更好的大家也可以分享。

- [https://github.com/xxlllq/system_architect](https://github.com/xxlllq/system_architect)
- [https://github.com/lisahust/FDExam_Note](https://github.com/lisahust/FDExam_Note)
- [https://github.com/synebula/SoftwareEngineerExam](https://github.com/synebula/SoftwareEngineerExam)
- [https://github.com/easonjim/ruankao](https://github.com/easonjim/ruankao) 关于软考的一些建议。
- [https://github.com/linfeng56/exam](https://github.com/linfeng56/exam) 网友自己的总结。
- [https://github.com/guanshilong/SystemArchitect](https://github.com/guanshilong/SystemArchitect) 网友自己 7 天考过高级架构师的经历。


### 个人整理资源

根据个人需求，对相关资源进行删减整理，打包并发布在阿里云盘，供大家下载使用，如有侵权，请联系我删除。

网盘中的资料相对更全面一些，包含本仓库中没有的教材以及其他一些资源（如极客时间的架构课程等），当然本仓库中有的网盘里也有，大家按需索取吧。

大家且用且珍惜哈！

> [https://www.aliyundrive.com/s/ufmLzTWF73W](https://www.aliyundrive.com/s/ufmLzTWF73W)


### 手机 APP 资源

目前我知道的可以刷软考题目的 app 有几款，一个是跨步软考的，一个就是下面将要推荐的软考通（已放置在根目录下 app 资源文件夹，大家直接安装即可，或者从豌豆荚自行下载），再就是希赛和 51CTO 题库小程序。

软考通的设计很简洁，没什么广告，资源相对比较齐全，除了个别错别字以外，平常刷个题还是非常不错的，主要还是免费的，可以利用闲暇时间刷一下。苹果版的直接在苹果商店下载即可。

跨步软考资源相对较老，目前也永久停更了，做一个补充作用还是可以的，直接从官网下载即可。

希赛的只是下载了 app，简单浏览过一次，界面还行，但后面也没有使用了，故无法做出评价。

51CTO 题库小程序也还行吧，就是多选设定的不够人性化，只能答一个空。

而我又不喜欢用小程序，所以我的主要刷题工具还是软考通。但是上面的答案和我手里的纸质答案有冲突，大家使用的时候需要注意。


### 视频资源

个人喜欢将视频下载到本地观看，但视频数量巨大，无法上传分享，因此这里只分享我下载过的视频链接好了。视频内容的话，大家就自行斟酌、选择观看吧，这里不做评价。

- ~~[https://www.bilibili.com/video/BV1fv411V7dH](https://www.bilibili.com/video/BV1fv411V7dH) 大家常说的 179，16 年版。~~
    - [https://www.aliyundrive.com/s/CzRtw9bFB18](https://www.aliyundrive.com/s/CzRtw9bFB18) 这里更新一个之前网友提供的版本，上面那个已经不存在啦！无法保证和上面的一模一样，因为我也没有看过。
- [https://www.bilibili.com/video/BV1HZ4y1N77x](https://www.bilibili.com/video/BV1HZ4y1N77x) 文老师精讲。
- [https://www.bilibili.com/video/BV1nh411X7rA](https://www.bilibili.com/video/BV1nh411X7rA) 文老师串讲。

至于如何下载 bilibili 的视频，大家就自行解决吧，相信你都能找到这里，找个下载方法还不简单吗？


## Credit

- GitHub.
- You All Guys!
