
# Description

<div class="content"><div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">N个人坐成一圈玩游戏。一开始我们把所有玩家按顺时针从1到N编号。首先第一回合是玩家1作为庄家。每个回合庄家都会随机（即按相等的概率）从卡牌堆里选择一张卡片，假设卡片上的数字为X，则庄家首先把卡片上的数字向所有玩家展示，然后按顺时针从庄家位置数第X个人将被处决即退出游戏。然后卡片将会被放回卡牌堆里并重新洗牌。被处决的人按顺时针的下一个人将会作为下一轮的庄家。那么经过N-1轮后最后只会剩下一个人，即为本次游戏的胜者。现在你预先知道了总共有M张卡片，也知道每张卡片上的数字。现在你需要确定每个玩家胜出的概率。</span></div>
<div><span style="font-size: medium">这里有一个简单的例子：</span></div>
<div><span style="font-size: medium">例如一共有4个玩家，有四张卡片分别写着3,4,5,6.</span></div>
<div><span style="font-size: medium">第一回合，庄家是玩家1，假设他选择了一张写着数字5的卡片。那么按顺时针数1,2,3,4,1，最后玩家1被踢出游戏。</span></div>
<div><span style="font-size: medium">第二回合，庄家就是玩家1的下一个人，即玩家2.假设玩家2这次选择了一张数字6，那么2,3,4,2,3,4，玩家4被踢出游戏。</span></div>
<div><span style="font-size: medium">第三回合，玩家2再一次成为庄家。如果这一次玩家2再次选了6，则玩家3被踢出游戏，最后的胜者就是玩家2.</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行包括两个整数N,M分别表示玩家个数和卡牌总数。</span></div>
<div><span style="font-size: medium">接下来一行是包含M个整数，分别给出每张卡片上写的数字。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出一行包含N个百分比形式给出的实数，四舍五入到两位小数。分别给出从玩家1到玩家N的胜出概率，每个概率之间用空格隔开，最后不要有空格。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
2 3 5 7 11<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">22.72% 17.12% 15.36% 25.44% 19.36%<br/>
 <br/>
输入样例2：<br/>
4 4<br/>
3 4 5 6<br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于100%的数据，有1&lt;=N&lt;=50 1&lt;=M&lt;=50 1&lt;=每张卡片上的数字&lt;=50<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

