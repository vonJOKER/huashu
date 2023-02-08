# 2023.2.3华数杯

## 组队

组队确实出了问题，这天灾人祸不可避免。

## 准备

倒是没做啥准备，本来这次比赛就是给美赛准备的，也不算是没有准备，用的easymcm的模板，改了预设格式（2023HSB），看了些论文，想到要画些图，熟悉了下zotero，就差不多这样。

## 选题

没啥说的，就两道题，mcm和icm各一道，mcm的不是数据题就可以确定做icm的题了。但是还是认真的查文献，理思路看了一遍，确定B题

## 比赛

对于我的工作而言，对自己还是比较满意的，首先是心态还是蛮好的，也能够预料到一些事情的发生，但是却没有能力阻止，反正买个教训不亏。

### 前两问，建立指标体系和社会预警模型

#### 第一问

其实网上的文献数不胜数，前人的工作做的足够多了，我们要做的就只是复现下就行了。这里层次分析法，专家调查法，文献什么法的，基本上都是这样。确定指标体系还看见了分为三级指标，这也是提供了思路，后面想到既然前面人的文献构建的指标体系已经很完善了，那我就没必要再去做一个什么样的工作了，我所做的就是一些文献有的列出来，没有的补充上，但是对于权重的再分配我这里看到了一篇论文用的是未确定测度理论，后来就想着用这个方法再加上文献去确定指标权重向量。至于指标间的关系，许多论文中DE，ISM还有DE-ISM的，那我就什么牛逼什么来，直接上DE-ISM，刚好看到一篇实验室指标用的这个方法的，直接照着抄就完事了。但是求解的过程有问题，网上没有现成的代码，于是只好一步一步的敲代码，还好matlab对于矩阵的运算真的是得天独厚，一边百度一边敲，还真就搞出来了。

#### 第二问

社会稳定预警模型，网上的也并不是预测模型而是评价模型，然后是建的一个标准分为四个等级的预警情况，好像认可度都挺高的，文献也不少。然后还有一篇文献看到了说社会稳定指数，也就是我论文中说的SRD Value会呈现周期性变化，我一想也是，社会稳定肯定是这样，那预测就是肯定会稳定呗，你说会趋于不稳定他也不会让啊。然后就只需要根据评分计算最终得分再对照看属于那种警报等级就行，所以就只需要对于评分再进行说明就好。然后文献也多，观点也都一样，就是突然性，影响性这些没啥好说的。

### 三四问

如果说我上面把一二问合在一起并不太好看的话，那么我把三四问合在一起肯定是不会有问题的。

选两个国家发生过颜色革命，一个成功一个失败，找到成功和失败的原因。因为这个问题背景性太强了，我先写的分析再写的解决。

#### 颜色革命

首先是颜色革命的介绍，这里前人出现了分歧，有人认为有以美国为首的西方国家参与推动的才叫颜色革命，有人认为是它们国家自己的问题，并不在于西方国家的推动。这也不好做出评判，我只选择相信是在西方国家的推动下，毕竟看看俄罗斯乌克兰就知道了。然后恰巧选的两个国家就是白俄罗斯颜色革命和乌克兰橙色革命。

#### 两场颜色革命的选取

如上，差点选了一个不是颜色革命的革命——法国大革命，不知道它们到底有没有看过什么是颜色革命。

#### 原因分析

##### 失败原因

我想法自然是跟前两问有关，那不就是因为没有破坏社会稳定性，不然再细分因为国家没赚到钱人民不满？没有继续分析而往下做了。

##### 成功原因

成功原因就不是破坏了社会稳定性了，也就是说，破坏社会稳定性是颜色革命成功的必要不充分条件。那这就很好说了，原因在美国为首的西方国家推动下，再看乌克兰和美国关系，一目了然噻。然后这里分析就直接文献就行了，自己不好评价政治，但是文献可以，所以论文中出现了大量引用。

### 摘要和信

这里全部做完之后思路就非常清晰了，研究目的是为了防止颜色革命发生或成功，然后提出的思路就是在社会稳定性的层面去考虑。所以一步步来先建立指标体系，再建立社会预警模型，紧接着选取几场颜色革命去看它们成功与否和社会稳定指数有什么关系，最后看我们该怎么防止提出建议，写封信。

### 全文总览

第一次做icm的题目，确实从开始没思路到后面思路已经十分清晰，感觉题目真的非常妙，只有你自己真正去查文献，了解背景，学模型去解决问题，你会惊讶地发现这并不需要什么高大上的模型和很好的编程能力，感觉主要论文写作能力要求很高，可惜我是机器翻译的，但是摘要还是比较满意的。

再就是真的能学到知识，对颜色革命也了解很多了，也学了一些评价模型。还是收获很大的。

## 反思

单挑能完成这样很满意了，队友的选取以后一定要谨慎。后面想到可以搞个控制变量法画伪代码图（这里没有去学看下还有什么方法），但是摆烂了，不应该。

# 致谢

首先是easymcm模板的开发者，虽然删去了中文宏包给我带来了些许麻烦。

再就是亚太一月的队友一直陪我聊天，回想起来应该算是比赛期间最高兴的事了。

也感谢两个队友，给我上了一课，30块买到了一个教训，也让我多了一些茶余饭后的谈资。

# 补

一封信还抄我的，你抄的都没我的好看捏
