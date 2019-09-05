# 题目描述


<h3>
题目描述
</h3>
<p>
农夫约翰的 N (1 ≤ N ≤ 50,000) 头奶牛，每天挤奶时总会按同样的顺序站好。一日，农夫约翰决定为奶牛们举行一个“终极飞盘”比赛。为简化问题，他将从奶牛队列中选出一个连续区间来进行游戏。不过，参加游戏的奶牛要玩的开心的话就不能在身高上差距太大。
</p>
<p>
农夫约翰制定了 Q (1 ≤ Q ≤ 200,000) 个预定的参赛组，给出它们的身高 (1 ≤ 身高 ≤ 1,000,000)。对每个参赛组，他需要你帮助确定组中最高牛和最低牛的身高差。
</p>
<h3>
输入格式
</h3>
<ul>
<li>
第 1 行: 两个空格隔开的整数，N 和 Q。
</li>
<li>
第 2..N+1 行: 第 i+1 行包含一个整数表示第 i 头牛的身高。
</li>
<li>
第 N+2..N+Q+1 行: 两个整数 A 和 B(1 ≤ A ≤ B ≤ N)，表示一个从 A 到 B 的参赛组区间。
</li>
</ul>
<h3>
输出格式
</h3>
<ul>
<li>
第 1..Q 行: 每行包含一个整数来表示区间上最大身高差。
</li>
</ul>
<h3>
样例输入
</h3>
<pre>6 3
1
7
3
4
2
5
1 5
4 6
2 2 </pre>
<h3>
样例输出
</h3>
<pre>6
3
0</pre>