
# Description

<div class="content"><div>在一个塔防小游戏中，有很多防线。每条防线由一排n个独立的防御体[1:n]进行防御。游戏过程中，会不断有敌人</div>
<div>对防线进行攻击，每次攻击会指定防御体[l:r]进行攻击力为a的攻击。第一防线具有护甲，护甲承受攻击后，对应</div>
<div>的防御体所受到的伤害为攻击力，但护甲承受的伤害总量到达一定程度后就会破碎，此时防御体所受的伤害加倍。</div>
<div>目前第一防线的力量充足，玩家致力于对后面的防线的建设，不过为确认游戏进度和第一防线的情况，玩家会不时</div>
<div>地将鼠标移动到第一防线的某个防御体上，以查看其所受到的伤害。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行，两个整数n,q，分别表示防御体个数以及攻击和查询的总数。</div>
<div>第二行，n个数，表示每个防御体护甲的承受能力pi。</div>
<div>接下来q行，每行可能具有如下形式</div>
<div>A l r a表示对防御体l,l+1,...,r进行攻击力为a的攻击</div>
<div>Q x表示查询防御体x目前所受到的伤害，初始时伤害为0</div>
<div>1 ≤ n ≤ 100000， 1 ≤ q ≤ 100000， 0 ≤ pi ≤ 1000000， 0 ≤ a ≤ 10000</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一行，一个整数，表示所有查询结果之和对1,000,000,009的余数</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
3 1 4 1 2<br/>
A 1 3 2<br/>
Q 2<br/>
A 1 4 1<br/>
Q 1<br/>
A 1 4 1<br/>
Q 2<br/>
Q 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">16<br/>
hint：<br/>
3/0 1/0 4/0 1/0 2/0<br/>
[A 1 3 2]<br/>
1/2 2 2/2 1/0 2/0<br/>
[Q 2] → 2<br/>
[A 1 4 1]<br/>
3 4 1/3 1 2/0<br/>
[Q 1] → 3<br/>
[A 1 4 1]<br/>
5 6 4 3 2/0<br/>
[Q 2] → 6<br/>
[Q 1] → 5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

