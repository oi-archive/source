<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Vasya喜欢玩塔防。<br/>
　　他来到了最后一关。为了顺利通关，他需要杀死Main Villain。Main Villain以1米每秒的速度从 ( - ∞, 0) 运动到 ( + ∞, 0) 。在所有点 (<i>x</i>, 1) 和 (<i>x</i>,  - 1)上Vasya可以修塔，其中<i>x</i>是整数。有三种类型的塔： 火、电、冰。不过，同一个点上只能修一个塔。每种类型的塔有一个固定的攻击半径和每秒伤害（除了冰塔）。如果某一时刻Main Villain在<i>k</i>座冰塔的攻击范围内，他的速度将被减少至 1/(<i>k</i> + 1) 。<br/>
　　现在每种塔的数目已知，Vasya希望知道能对Main Villain造成最大伤害的塔的布置方案。<br/>
　　所有距离以米为单位给出。可以将Main Villain和塔近似看做平面上的点。Main Villain在一座塔的攻击范围内是指他与塔的欧几里得距离小于等于塔的攻击半径。<br/>
<b>输入格式</b><b></b><br/>
　　第一行是三个整数 <i>nf</i>, <i>ne</i> 和 <i>ns</i> — 分别是可用的火、电、冰塔总数 (0 ≤ <i>nf</i>, <i>ne</i>, <i>ns</i> ≤ 20, 1 ≤ <i>nf</i> + <i>ne</i> + <i>ns</i> ≤ 20)。<br/>
　　第二行包含三个整数 <i>rf</i>, <i>re</i> 和 <i>rs</i> (1 ≤ <i>rf</i>, <i>re</i>, <i>rs</i> ≤ 1000) — 表示火、电、冰塔的攻击半径。<br/>
　　第三行包含两个整数 <i>df</i> 和 <i>de</i> (1 ≤ <i>df</i>, <i>de</i> ≤ 1000) — 表示火、电塔对Main Villain的每秒伤害（如果在攻击范围内的话）。<br/>
<b>输出格式</b><b></b><br/>
　　输出一个实数，即最大的伤害。绝对误差不超过10<sup> - 6</sup></div>
# 样例输入

<div class="pddata">1 0 0<br/>
10 10 10<br/>
100 100</div>
# 样例输出

<div class="pddata">1989.97487421</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">数据点<br/>
</td><td valign="top" style="border:solid 1.0pt">数据特征<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">同样例<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">1 0 1<br/>
10 10 10<br/>
100 100<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3-5<br/>
</td><td valign="top" style="border:solid 1.0pt">nf+ne+ns&lt;=5<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9,11,13,19<br/>
</td><td valign="top" style="border:solid 1.0pt">nf=0<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">15,17<br/>
</td><td valign="top" style="border:solid 1.0pt">ne=0<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">剩下9个点<br/>
</td><td valign="top" style="border:solid 1.0pt"><i>nf</i> + <i>ne</i> + <i>ns</i> ≤ 20<br/>
</td></tr></tbody></table></div>

</div>