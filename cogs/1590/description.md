# 题目描述


<h3>
【题目描述】
</h3>
<p>
农夫约翰的奶牛（1≤n≤20），总是方便的标记为1……N，或许应该叫N项全能，因为有N个不同的事件（通常有10个事件）。
</p>
<p>
牛i有一个s_ij的技能水平（1&lt;=s_ij＜＝1000），是牛i在参与项目j时会得到的分数。每头奶牛必须且只能参加一个项目，每个事件必须有一些牛参加。
</p>
<p>
所有奶牛总得分为他们参加项目事件中的技能水平和。然而，项目的裁判如果有深刻印象，可以给出奖励分。评委可以给出B种奖励分（1≤B≤20）。奖励分i有三部分：如果奶牛在前k_i事件（包括这些事件其他牛的分数）获得了至少p_i（1&lt; = p_i＜＝40000）分，他们将获得额外的a_i（1&lt;=a_i&lt;=1000）分（前k项触发的奖励积分不算到前k项的分数和，但算到之后的分数和中）。
</p>
<p>
例如，让我们考虑n = 3头牛技能水平如下：
</p>
<center>
<table height="150" border="1" width="237">
<tbody>
<tr>
<td valign="middle" align="center" width="48">
 
</td>
<td colspan="4" valign="middle" align="center">
cow
</td>
</tr>
<tr>
<td rowspan="4" valign="middle" align="center">
event
</td>
<td valign="middle" align="center" width="39">
 
</td>
<td valign="middle" align="center" width="42">
1
</td>
<td valign="middle" align="center" width="44">
2
</td>
<td valign="middle" align="center" width="30">
3
</td>
</tr>
<tr>
<td valign="middle" align="center">
1
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
5
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
1
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
7
</td>
</tr>
<tr>
<td valign="middle" align="center">
2
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
2
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
2
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
4
</td>
</tr>
<tr>
<td valign="middle" align="center">
3
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
4
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
2
</td>
<td valign="middle" bgcolor="#FFFF66" align="center">
1
</td>
</tr>
</tbody>
</table>
</center>
<h3>
【输入格式】
</h3>
<p>
第1行为N和B；
</p>
<p>
接下来有B行（2--B+1），其中第i+1行为 K_i, P_i,A_i；
</p>
<p>
再接下来有N行（B+2--B+1+N），其中第B+N+j行表示 s_j1...s_jN. 。
</p>
<h3>
【输出格式】
</h3>
<p>
输出只有一行，即牛得到的最大分数，包括奖励分。
</p>
<h3>
【样例输入】
</h3>
<pre>3 1
2 7 6
5 1 7
2 2 4
4 2 1
</pre>
<h3>
【样例输出】
</h3>
<pre>17</pre>
<h3>
【提示】
</h3>
<p>
输出解释：
</p>
<p>
牛1参与项目1，牛2参与项目3，牛3参与项目2。
</p>
<h3>
【来源】
</h3>
<p>
USACO Feb14
</p>
