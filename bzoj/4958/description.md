
# Description

<div class="content"><div>你的对手太坏了! 在每年的年度石头剪刀布锦标赛上,你总是能进总决赛。 (你的石头技巧无与伦比,你的布震撼人</div>
<div>心! 不过你的剪刀需要练练) 但是每年,你的对手总是能打败你,即使他的操作看上去是完全是随机的!而且他发布</div>
<div>新闻声称他无可匹敌。他的秘诀是什么?幸运的是,你认为你已经找到了。就在今年,锦标赛之前的时候,你发现他拜</div>
<div>访了城里的许多萨满。啊哈! 原来他在使用超自然力量对付你! 你觉得这次可以好好玩一玩了。所以你拜访了一群</div>
<div>算命师,他们用塔罗牌帮你预测了对手在比赛中会使用的操作序列。然而,你最初的兴奋已经过去了,你现在感觉自</div>
<div>己有点智障。这怎么可能赢?最后你才发现你已经对这种随机预测的欺诈行为付出了许多钱。好吧,你可能会在比赛</div>
<div>中留意其中一些预测。但是用哪些预测好呢?在总决赛中,你和你的对手将玩n轮石头剪刀布。每一轮中,你和你的对</div>
<div>手会从三种选择 (石头、剪刀、布) 中选择一个操作。根据你们的选择来确定每一轮的胜利者 (实际上与本题没太</div>
<div>大关系) 。给定总决赛的长度和一些预测,请你按照在总决赛中作为你对手操作的一个连续子序列出现的可能性排</div>
<div>序它们,这里假设对方每一轮的选择是独立随机的。</div></div>

# Input

<div class="content"><div>第一行包含两个整数n(1≤n≤10^6)和s(1≤s≤10),分别表示总决赛的轮数和序列的数量。</div>
<div>接下来s行,每行描述一种预测,包含一个由&#39;R&#39;,&#39;P&#39;,&#39;S&#39; 组成的字符串。</div>
<div>所有的预测拥有相同的长度,长度在1到n之间(含边界),且不会超过10^5 。</div></div>

# Output

<div class="content"><div>输出按照在总决赛出现的可能性降序输出所有的预测。</div>
<div>对于可能性相同的预测,按照他们在输入中的顺序输出。</div></div>

# Sample Input

<div class="content"><span class="sampledata">样例1<br/>
3 4<br/>
PP<br/>
RR<br/>
PS<br/>
SS<br/>
样例2<br/>
20 3<br/>
PRSPS<br/>
SSSSS<br/>
PPSPP</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例1<br/>
PS<br/>
PP<br/>
RR<br/>
SS<br/>
样例2<br/>
PRSPS<br/>
PPSPP<br/>
SSSSS</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供翻译">鸣谢Tangjz提供翻译</a></p></div>

