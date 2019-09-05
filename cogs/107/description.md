# 题目描述


<p>
【问题背景】
</p>
<p>
近来，一种新的传染病肆虐全球。蓬莱国也发现了零星感染者，为防止该病在蓬莱国大范围流行，该国政府 决定不惜一切代价控制传染病的蔓延。不幸的是，由于人们尚未完全认识这种传染病，难以准确判别病毒携带者，更没有研制出疫苗以保护易感人群。于是，蓬莱国 的疾病控制中心决定采取切断传播途径的方法控制疾病传播。经过 WHO （世界卫生组织）以及全球各国科研部门的努力，这种新兴传染病的传播途径和控制方法已经研究消除，剩下的任务就是由你协助蓬莱国疾控中心制定一个有效的控 制办法。
</p>
<p>
【问题描述】
</p>
<p>
研究表明，这种传染病的传播具有两种很特殊的性质；第一是它的 传播途径是树型的，一个人 X 只可能被某个特定的人 Y 感染，只要 Y 不得病，或者是 XY 之间的传播途径被切断，则 X 就不会得病。第二是，这种疾病的传播有周期性，在一个疾病传播周期之内，传染病将只会感染一代患者，而不会再传播给下一代。
</p>
<p>
这 些性质大大减轻了蓬莱国疾病防控的压力，并且他们已经得到了国内部分易感人群的潜在传播途径图（一棵树）。但是，麻烦还没有结束。由于蓬莱国疾控中心人手 不够，同时也缺乏强大的技术，以致他们在一个疾病传播周期内，只能设法切断一条传播途径，而没有被控制的传播途径就会引起更多的易感人群被感染（也就是与 当前已经被感染的人有传播途径相连，且连接途径没有被切断的人群）。当不可能有健康人被感染时，疾病就中止传播。所以，蓬莱国疾控中心要制定出一个切断传 播途径的顺序，以使尽量少的人被感染。
</p>
<p>
你的程序要针对给定的树，找出合适的切断顺序。
</p>
<p>
【输入格式】
</p>
<p>
输入格式的第一行是两个整数 n （ 1≤n≤300 ）和 p 。接下来 p 行，每一行有两个整数 i 和 j ，表示节点 i 和 j 间有边相连（意即，第 i 人和第 j 人之间有传播途径相连）。其中节点1 是已经被感染的患者。
</p>
<p>
【输出格式】
</p>
<p>
只有一行，输出总共被感染的人数。
</p>
<p>
【输入样例】
</p>
<p>
7 6<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
3 6<br/>
3 7
</p>
<p>
【输出样例】
</p>
<p>
3
</p>