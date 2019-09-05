# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
农场冬天寒冷的天气令人厌倦，贝茜奶牛计划飞到一个温暖的目的地度假。不幸的是，她发现只有一家航空公司bovinia，愿意给牛出售门票，这些票结构上有点复杂。
</p>
<p>
bovinia航空公司拥有N架飞机（1≤N≤500），其中每架飞机有一个具体的&#34;航线&#34;，连接两个或两个以上的城市。例如，一个飞机的可能飞行路线，开始在城市1，然后飞到城市5，然后飞到城市2，最后飞到城市8。没有城市在航线中出现多次。如果她选择使用一个路线，她可以在沿途的任何城市下来，也可以在路线中后面的沿线城市再次上飞机。她不需要在第一个城市下飞机，也不需要在最后的城市上飞机。每条航线具有一定的费用，如果她采用路线的任何部分，贝茜必须支付成本，可以不考虑她走访沿线城市数量。
</p>
<p>
贝茜想找到最便宜的旅行路线，从她的农场（城市A）到达她忠情目的地（城市B）。她不想使用一个复杂的路线，以免造成混乱。她只想用一个单一的路线。请帮助她选择线路，和她必须支付的最低成本。
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
输入的第一行包含A，B，N，用空格隔开。
</p>
<p>
接下来2N行描述了可用的路线，每条路线有两行。第一行包含使用路线的成本（一个整数,范围1..1000），与沿线城市的数量（一个范围在1..500的整数）。第二行包含一个列表的沿线为城市。每个城市都是确定的整数,范围是1..10000。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出一个整数，表示路茜从城市A到城市B旅行的最低成本，如果没有这样的路线，输出-1。
</p>
<h3>
【样例输入】
</h3>
<pre>1 2 3
3 3
3 2 1
4 4
2 1 4 3
8 5
4 1 7 8 2</pre>
<h3>
【样例输出】
</h3>
<pre>8</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
样例解释：
</p>
<p>
虽然有一个便宜的方案，使用两个路线（使用路线2从城市1城市3，然后使用路线1从城市3到2），但贝茜只允许使用一个路线，所以她必须使用路线3，成本为8。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>