# 题目描述


<p>
<strong>[问题描述] </strong> 
</p>
<p align="left">
晚会上大家在玩一款“暴力摩托”的游戏，它拥有非常逼真的画面和音响效果，如疾驰而过的汽车呼啸声，摩托车的引擎声和转弯时轮胎与地面摩擦而产生的声音。而且它在游戏中加入了对抗成份，比赛中你可以使用拳、脚去干扰对方，使其落后于你，是不是很卑鄙啊 ? 游戏中千万不能手下留情，因为对手会主动攻击你。如果遇到开摩托车的警察，虽然也可以对他踢上一脚，但可得小心点呀，万一被他们捉住了，那就 GAME OVER 啦!
</p>
<p align="left">
当然了，车子总是要加油的咯，已知赛道长 S公里（S≤10000整数，且为10的倍数），赛车的油耗Q=1，即 1公里 路耗 1个单位的油。Q不变，赛车的油箱为无穷大，同时在沿途的任何地方都可以加油。 约定，每次加油的数量为整数，且为 10的倍数，赛车的速度与赛车加油后的总油量有关。其关系如下表列出：
</p>
<table cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td width="127" valign="top">
<p>
总油量
</p>
</td>
<td width="168" valign="top">
<p>
车速（公里 / 小时）
</p>
</td>
</tr>
<tr>
<td width="127" valign="top">
<p>
≤10
</p>
</td>
<td width="168" valign="top">
<p>
100
</p>
</td>
</tr>
<tr>
<td width="127" valign="top">
<p>
（ 10 ， 20 ]
</p>
</td>
<td width="168" valign="top">
<p>
90
</p>
</td>
</tr>
<tr>
<td width="127" valign="top">
<p>
（ 20 ， 30 ]
</p>
</td>
<td width="168" valign="top">
<p>
80
</p>
</td>
</tr>
<tr>
<td width="127" valign="top">
<p>
（ 30 ， 40 ]
</p>
</td>
<td width="168" valign="top">
<p>
75
</p>
</td>
</tr>
<tr>
<td width="127" valign="top">
<p>
（ 40 ， + ∞ ）
</p>
</td>
<td width="168" valign="top">
<p>
70
</p>
</td>
</tr>
</tbody>
</table>
<p>
 
</p>
<p>
同时，汽车每加油一次需要耗费 T分钟（T&lt;=100不论加油多少，开始时的加油不计时间）
</p>
<p>
当 S，T给出之后，选择一个最优的加油方案。使汽车以最少时间跑完全程。
</p>
<p>
例如：当 S=40，T=6（分钟），加油的方案有许多种，列出一些：
</p>
<p>
1）起点加油40，用时40/75≈0.53小时
</p>
<p>
2）起点加油20，中途加20，用时20/90+20/90+6/60（化为小时）≈ 0.54 小时
</p>
<p>
<strong>[输入文件] </strong> 
</p>
<p>
一行，为两个整数 S、T。
</p>
<p>
<strong>[输出文件] </strong> 
</p>
<p>
输出一行，为 最少用时（保留二位小数）
</p>
<p>
<strong>[输入样例] </strong> 
</p>
<p align="left">
40 6
</p>
<p>
<strong>[输出样例] </strong> 
</p>
<p>
0.53
</p>
