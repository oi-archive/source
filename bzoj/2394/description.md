
# Description

<div class="content"><div style="text-indent: 21pt">风行者是倒塔中非常热门的英雄之一，他的技能穿云箭可以对一条直线上的敌人同时造成伤害，第一个中箭的人初始伤害是B，后面中箭的人伤害比前面的人减少P%（比如：穿云箭经过的第一个人受到的伤害是B，经过的第二个人受到的伤害就是trunc(B*(1-P%))）。</div>
<div style="text-indent: 21pt">现在风行者的面前有N个小兵，每个小兵的位置(Xi,Yi)，剩余血量Hi，以及杀死这个小兵可以得到的金钱数Gi（当这个小兵中了箭以后剩下的血量小于等于0则视该小兵被杀死）。原本风行者想把所有的小兵都杀死以得到所有的金钱，但是时间紧迫，他妈妈叫他回家看天线宝宝。无奈，他只能射一箭。他想知道这一箭要移动到哪里，怎么射才可以得到最多的金钱。（假设穿云箭的距离无限长）</div>
<div> </div></div>

# Input

<div class="content"><div><span>    </span>第一行，两个数字N，B，P。接下来N行，每行三个数字Xi Hi Gi。所有的输入数据都是整数</div></div>

# Output

<div class="content"><div><span>    </span>就一行，可以得到最多的金钱数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">1 1 1<br/>
1 1 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模<br/><br/>
20%的数据N&lt;=20<br/><br/>
50%的数据N&lt;=100 B&lt;=100 P&lt;=50<br/><br/>
100%的数据N&lt;=1000<br/><br/>
所有数据的x,y,h,g以及b,均为0~10000之内的整数，p为0..99之间的整数</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

