# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
lemon最近迷上了优秀考智商的卡牌游戏（垃圾氪金）——游戏王。最为集换式卡牌鼻祖级的游戏，游戏王伴随了许多人的一生。在k社无节操地维护环境下，游戏王充满了无穷的可能性。但是lemon不知道如何组卡组（游戏王卡片出得太多了！lemon记不完），所以他找来了你来帮忙。现在他只想选一些怪兽卡作为自己的魂卡（们），（lemon：我又不是主角可以印卡逆天，攻防当然越高越好啦！！！）
</p>
<p>
有如下规则：
</p>
<p>
1.卡池有t张怪兽牌。
</p>
<p>
2.lemon需要q次查询，给你一个flag，
</p>
<p>
当flag=1时，每次查询区间[l,r]上攻击力最大的牌的攻击力a，
</p>
<p>
当flag=0时，每次查询区间[l,r]上防御力最大的牌的防御力d。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入第一行有两个整数t,q分别表示卡池中卡牌总数，与查询次数。
</p>
<p>
接下来t行，每行三个整数Ci，Ai，Di，分别表示卡片种类，卡片攻击力，卡片防御力。
</p>
<p>
接下来q行，每行三个整数fi，li，ri，f如题目描述中所述，表示查询类型，l，r表示查询区间，数据保证r&gt;l，f只为1与0。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出共q行，每行一个整数，表示所询问的答案。
</p>
<h3>
【样例输入】
</h3>
<pre>6 2
1 4 9
1 4 9
2 3 4
3 4 5
4 5 20
5 30 5
1 2 3
0 1 5
</pre>
<h3>
【样例输出】
</h3>
<pre>4
20
</pre>
<h3>
【提示】
</h3>
<p>
对于30%的数据t≤100000,q≤100000
</p>
<p>
对于60%的数据t≤100000,q≤1000000
</p>
<p>
对于100%的数据t≤1000000,q≤1000000
</p>
<p>
所有数据均为非负整数，且都不大于2147483647。
</p>
<p>
数据保证合法，一道水题。
</p>
<p>
TANKS FOR YOUR VIEW
</p>
<h3>
【来源】
</h3>
<p>
lemonoil
</p>