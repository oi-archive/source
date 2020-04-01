
# Description

<div class="content"><div>
<div>【题目背景】</div>
<div>“虽然不知道那两台是谁干掉的，不过任务完成了。”一一次祖伽密．</div>
<div>【题意描述】</div>
<div>敌方有n台人形兵器，每台的攻击力为Ai，护甲值为Di。我方只有一台人形兵器，攻击力为ATK。战斗看作回合制，</div>
<div>每回合进程如下：</div>
<div>  ·1 我方选择对方某台人形兵器并攻击，令其护甲值减少ATK，</div>
<div>若护甲值&lt;0则被破坏。</div>
<div>  ·2 敌方每台未被破坏的人形兵器攻击我方基地造成Ai点损失。</div>
<div>但是，在第一回合开始之前，某两台敌方的人形兵器被干掉了(秒杀）。问最好情况下，我方基地会受到多少点损</div>
<div>失。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行两个数n，ATK，表示敌方人形兵器数量和我方人形兵器攻击力。</div>
<div>接下来n行，每行两个数A，Di，表示对方第i台人形兵器的攻击力和护甲值。</div>
<div>3&lt;=n&lt;=3×10^5，Ai，Di&lt;=10^4，ATK&lt;10^4</div>
</div>
<p></p></div>

# Output

<div class="content"><div>只一行，一个数，表示最好情况下我方基地会受到的损失总和。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 7<br/>
30 8<br/>
7 35<br/>
1 209</span></div>

# Sample Output

<div class="content"><span class="sampledata">28<br/>
【样例说明】<br/>
最好情况下，被秒杀的是敌方1、3号人形兵器，接下来需要5回合解决对方的2号人形兵器，对方共攻击4次，总计<br/>
造成28点伤害。可以证明没有更优的情况。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

