English version repo and Gitbook is on [english branch](https://github.com/labuladong/fucking-algorithm/tree/english). Just enjoy：)

# 前言

本仓库总共 60 多篇原创文章，基本上都是基于 LeetCode 的题目，涵盖了所有题型和技巧，而且一定要做到**举一反三，通俗易懂**，绝不是简单的代码堆砌，后面有目录。

我先吐槽几句。**刷题刷题，刷的是题，培养的是思维，本仓库的目的就是传递这种算法思维**。我要是只写一个包含 LeetCode 题目代码的仓库，有个锤子用？没有思路解释，没有思维框架，顶多写个时间复杂度，那玩意一眼就能看出来。

只想要答案的话很容易，题目评论区五花八门的答案，动不动就秀 python 一行代码解决，有那么多人点赞。问题是，你去做算法题，是去学习编程语言的奇技淫巧的，还是学习算法思维的呢？你的快乐，到底源自复制别人的一行代码通过测试，已完成题目 +1，还是源自自己通过逻辑推理和算法框架不看答案写出解法？

网上总有大佬喷我，说我写这玩意太基础了，根本没必要啰嗦。我只能说大家刷算法就是找工作吃饭的，不是打竞赛的，我也是一路摸爬滚打过来的，我们要的是清楚明白有所得，不是故弄玄虚无所指。不想办法做到通俗易懂，难道要上来先把《算法导论》吹上天，然后把人家都心怀敬仰地劝退？别的不说，公众号几万读者，PDF 版本上万次下载，联系我的出版社都好几家，说明质量还过得去吧？

**做啥事情做多了，都能发现套路的，我把各种算法套路框架总结出来，相信可以帮助其他人少走弯路**。我这个纯靠自学的小童鞋，花了一年时间刷题和总结，自己写了一份算法小抄，后面有目录，这里就不废话了。

### 使用方法

1、**先给本仓库点个 star，满足一下我的虚荣心**，文章质量绝对值你一个 star。我还在继续创作，给我一点继续写文的动力，感谢。

2、可以在我的 Gitbook 或者 GitHub pages 或者 [我的知乎](https://www.zhihu.com/people/fdl-72) 上查看所有文章，公众号更新后会尽快更新网页，建议收藏方便电脑端查看文章（之所以同时搞 Gitbook 和 GitHub pages，是因为有的地区的读者反映 Gitbook 经常加载不出来，你可以自行选择）：

Gitbook 地址（推荐）：https://labuladong.gitbook.io/algo/

GitHub page 地址：https://labuladong.github.io/ebook/

3、可以关注我的公众号 **labuladong** 及时获取更新。我不喜欢转载乱七八糟的低质文章，**坚持高质量原创，说是最良心最硬核的技术公众号都不为过**。

本仓库的文章就是从公众号里整理出来的**一部分**内容，我主要发文平台是微信公众号，公众号后台回复关键词【电子书】可以获得这份小抄的电子书版本，最近准备出版，限时免费下载；回复【**加群**】可以加入我们的刷题群，和大家一起讨论算法问题，分享内推机会：

<img src="./pictures/qrcode.jpg" width = "200" align=center />

其他的先不多说了，直接上干货吧，我们一起日穿 LeetCode，感受一下支配算法的乐趣。

**PS：如果想下载此仓库到本地学习，不要用 git 命令下载，点击 GitHub 网页上的下载按钮直接下载 zip 文件，这样就不会下载 git 历史，大大加快下载速度**。

# 目录

* 第零章、必读系列
  * [学习算法和刷题的框架思维](算法思维系列/学习数据结构和算法的高效方法.md) 【done】
  * [学习数据结构和算法读什么书](算法思维系列/为什么推荐算法4.md) 【done】
  * [动态规划解题框架](动态规划系列/动态规划详解进阶.md) 【done】
  * [动态规划答疑篇](动态规划系列/最优子结构.md) 【done】
  * [回溯算法解题框架](算法思维系列/回溯算法详解修订版.md) 【done】
  * [为了学会二分查找，我写了首诗](算法思维系列/二分查找详解.md)【 done】
  * [滑动窗口解题框架](算法思维系列/滑动窗口技巧.md) 【done】
  * [双指针技巧解题框架](算法思维系列/双指针技巧.md)【done】
  * [Linux的进程、线程、文件描述符是什么](技术/linux进程.md)
  * [Git/SQL/正则表达式的在线练习平台](技术/在线练习平台.md)
* 第一章、动态规划系列
  * [动态规划详解](动态规划系列/动态规划详解进阶.md)【done】
  * [动态规划答疑篇](动态规划系列/最优子结构.md)【done】
  * [动态规划设计：最长递增子序列](动态规划系列/动态规划设计：最长递增子序列.md)【done】
  * [编辑距离](动态规划系列/编辑距离.md)【done】
  * [经典动态规划问题：高楼扔鸡蛋](动态规划系列/高楼扔鸡蛋问题.md)【done】
  * [经典动态规划问题：高楼扔鸡蛋（进阶）](动态规划系列/高楼扔鸡蛋进阶.md)【done】
  * [动态规划之子序列问题解题模板](动态规划系列/子序列问题模板.md)【done】
  * [动态规划之博弈问题](动态规划系列/动态规划之博弈问题.md)【done】
  * [贪心算法之区间调度问题](动态规划系列/贪心算法之区间调度问题.md)【done】
  * [动态规划之KMP字符匹配算法](动态规划系列/动态规划之KMP字符匹配算法.md)【done】
  * [团灭 LeetCode 股票买卖问题](动态规划系列/团灭股票问题.md)【done】
  * [团灭 LeetCode 打家劫舍问题](动态规划系列/抢房子.md)【done】
  * [动态规划之四键键盘](动态规划系列/动态规划之四键键盘.md)【done】
  * [动态规划之正则表达](动态规划系列/动态规划之正则表达.md)【done】
  * [最长公共子序列](动态规划系列/最长公共子序列.md)【done】
* 第二章、数据结构系列
  * [学习算法和刷题的思路指南](算法思维系列/学习数据结构和算法的高效方法.md)
  * [学习数据结构和算法读什么书](算法思维系列/为什么推荐算法4.md)
  * [二叉堆详解实现优先级队列](数据结构系列/二叉堆详解实现优先级队列.md)
  * [LRU算法详解](高频面试系列/LRU算法.md)
  * [二叉搜索树操作集锦](数据结构系列/二叉搜索树操作集锦.md)
  * [特殊数据结构：单调栈](数据结构系列/单调栈.md)
  * [特殊数据结构：单调队列](数据结构系列/单调队列.md)
  * [设计Twitter](数据结构系列/设计Twitter.md)
  * [递归反转链表的一部分](数据结构系列/递归反转链表的一部分.md)
  * [队列实现栈\|栈实现队列](数据结构系列/队列实现栈栈实现队列.md)
* 第三章、算法思维系列
  * [算法学习之路](算法思维系列/算法学习之路.md)
  * [回溯算法详解](算法思维系列/回溯算法详解修订版.md)
  * [回溯算法团灭排列、组合、子集问题](高频面试系列/子集排列组合.md)
  * [二分查找详解](算法思维系列/二分查找详解.md)
  * [双指针技巧总结](算法思维系列/双指针技巧.md)
  * [滑动窗口技巧](算法思维系列/滑动窗口技巧.md)
  * [twoSum问题的核心思想](算法思维系列/twoSum问题的核心思想.md)
  * [常用的位操作](算法思维系列/常用的位操作.md)
  * [拆解复杂问题：实现计算器](数据结构系列/实现计算器.md)
  * [烧饼排序](算法思维系列/烧饼排序.md)
  * [前缀和技巧](算法思维系列/前缀和技巧.md)
  * [字符串乘法](算法思维系列/字符串乘法.md)
  * [FloodFill算法详解及应用](算法思维系列/FloodFill算法详解及应用.md)
  * [区间调度之区间合并问题](算法思维系列/区间调度问题之区间合并.md)
  * [区间调度之区间交集问题](算法思维系列/区间交集问题.md)
  * [信封嵌套问题](算法思维系列/信封嵌套问题.md)
  * [几个反直觉的概率问题](算法思维系列/几个反直觉的概率问题.md)
  * [洗牌算法](算法思维系列/洗牌算法.md)
  * [递归详解](算法思维系列/递归详解.md)
* 第四章、高频面试系列
  * [如何实现LRU算法](高频面试系列/LRU算法.md)
  * [如何高效寻找素数](高频面试系列/打印素数.md)
  * [如何计算编辑距离](动态规划系列/编辑距离.md)
  * [如何运用二分查找算法](高频面试系列/koko偷香蕉.md)
  * [如何高效解决接雨水问题](高频面试系列/接雨水.md)
  * [如何去除有序数组的重复元素](高频面试系列/如何去除有序数组的重复元素.md)
  * [如何寻找最长回文子串](高频面试系列/最长回文子串.md)
  * [如何k个一组反转链表](高频面试系列/k个一组反转链表.md)
  * [如何判定括号合法性](高频面试系列/合法括号判定.md)
  * [如何寻找消失的元素](高频面试系列/消失的元素.md)
  * [如何寻找缺失和重复的元素](高频面试系列/缺失和重复的元素.md)
  * [如何判断回文链表](高频面试系列/判断回文链表.md)
  * [如何在无限序列中随机抽取元素](高频面试系列/水塘抽样.md)
  * [如何调度考生的座位](高频面试系列/座位调度.md)
  * [Union-Find算法详解](算法思维系列/UnionFind算法详解.md)
  * [Union-Find算法应用](算法思维系列/UnionFind算法应用.md)
  * [一行代码就能解决的算法题](高频面试系列/一行代码解决的智力题.md)
  * [二分查找高效判定子序列](高频面试系列/二分查找判定子序列.md)
* 第五章、计算机技术
  * [Linux的进程、线程、文件描述符是什么](技术/linux进程.md)
  * [一文看懂 session 和 cookie](技术/session和cookie.md)
  * [关于 Linux shell 你必须知道的](技术/linuxshell.md)
  * [加密算法的前身今世](技术/密码技术.md)
  * [Git/SQL/正则表达式的在线练习平台](技术/在线练习平台.md)

# 感谢如下大佬参与翻译

按照昵称字典序排名：

[ABCpril](https://github.com/ABCpril), 
[andavid](https://github.com/andavid), 
[bryceustc](https://github.com/bryceustc), 
[build2645](https://github.com/build2645), 
[CarrieOn](https://github.com/CarrieOn), 
[cooker](https://github.com/xiaochuhub), 
[Dong Wang](https://github.com/Coder2Programmer), 
[ExcaliburEX](https://github.com/ExcaliburEX), 
[floatLig](https://github.com/floatLig), 
[ForeverSolar](https://github.com/foreversolar), 
[Fulin Li](https://fulinli.github.io/), 
[Funnyyanne](https://github.com/Funnyyanne), 
[GYHHAHA](https://github.com/GYHHAHA), 
[Hi_archer](https://hiarcher.top/), 
[Iruze](https://github.com/Iruze), 
[Jieyixia](https://github.com/Jieyixia), 
[Justin](https://github.com/Justin-YGG), 
[Kevin](https://github.com/Kevin-free), 
[Lrc123](https://github.com/Lrc123), 
[lriy](https://github.com/lriy), 
[Lyjeeq](https://github.com/Lyjeeq), 
[MasonShu](https://greenwichmt.github.io/), 
[Master-cai](https://github.com/Master-cai), 
[miaoxiaozui2017](https://github.com/miaoxiaozui2017), 
[natsunoyoru97](https://github.com/natsunoyoru97), 
[nettee](https://github.com/nettee), 
[PaperJets](https://github.com/PaperJets), 
[qy-yang](https://github.com/qy-yang), 
[realism0331](https://github.com/realism0331), 
[SCUhzs](https://github.com/HuangZiSheng001), 
[Seaworth](https://github.com/Seaworth), 
[shazi4399](https://github.com/shazi4399), 
[ShuozheLi](https://github.com/ShuoZheLi/), 
[sinjoywong](https://blog.csdn.net/SinjoyWong), 
[sunqiuming526](https://github.com/sunqiuming526), 
[Tianhao Zhou](https://github.com/tianhaoz95), 
[timmmGZ](https://github.com/timmmGZ), 
[tommytim0515](https://github.com/tommytim0515), 
[upbin](https://github.com/upbin), 
[wadegrc](https://github.com/wadegrc), 
[walsvid](https://github.com/walsvid), 
[warmingkkk](https://github.com/warmingkkk), 
[Wonderxie](https://github.com/Wonderxie), 
[wsyzxxxx](https://github.com/wsyzxxxx), 
[xiaodp](https://github.com/xiaodp), 
[youyun](https://github.com/youyun), 
[yx-tan](https://github.com/yx-tan), 
[Zero](https://github.com/Mr2er0), 
[Ziming](https://github.com/ML-ZimingMeng/LeetCode-Python3)

# Donate

如果本仓库对你有帮助，可以请作者喝杯速溶咖啡

<img src="pictures/pay.jpg" width = "200" align=center />
