
# Description

<div class="content"><p>Claris想要铸一把剑，这把剑必须符合他的审美，具体来说，我们可以把这把剑的不同地方的宽度看成一个序列，这个序列要满足以下条件：<br/>
1.每个元素都是正整数（你的宽度不可能是负数吧）<br/>
2.每个元素不能超过M，太宽了如果比Claris身高还高怎么办（你可以认为Claris的身高就是M）<br/>
3.相邻两个元素的差的绝对值必须是1（如果是0，则这个地方不是锯齿，杀伤力不够，如果太大，又太丑了）<br/>
4.第一个元素的值必须是1（剑尖必须是最窄的地方）<br/>
他想知道有多少把长度不超过N（即宽度的序列长度不超过N）的合法的本质不同的剑。<br/>
我们认为两把剑本质不同，当且仅当存在至少一个宽度，在两把剑的宽度序列里面出现次数不一样。<br/>
比如{1,2,3}和{1,3,2}是本质相同的<br/>
{1,2,3}和{1,2,1}则是本质不同的</p></div>

# Input

<div class="content"><p>只有两个整数，表示N,M (数据保证$N,M \leq 2000000$)</p></div>

# Output

<div class="content"><p>只有一个整数，表示答案对$10^9+7$取模的结果</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p><p>样例解释<br/><br/>
<br/><br/>
所有本质不同的合法的剑有如下：<br/><br/>
<br/><br/>
{1}<br/><br/>
{1,2}<br/><br/>
{1,2,3}<br/><br/>
{1,2,1}<br/><br/>
{1,2,3,2}<br/><br/>
{1,2,1,2}<br/><br/>
{1,2,3,2,3}<br/><br/>
{1,2,3,2,1}<br/><br/>
{1,2,1,2,1}</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By lyzy">By lyzy</a></p></div>

