# 题目描述


<h3>
【题目描述】
</h3>
<p>
 wzp 热衷于收集各种兵器。倚天剑的内心是拒绝的，因为 wzp 会渐渐不再使用它。
</p>
<p>
现在我们来观察一下倚天剑愤怒的具体现象。wzp 按顺序收集了 n 件兵器(显然不包括倚天剑)，每件会使倚天剑的心情变化 a[i](可以为正数，不要问我为什么倚天剑会变高兴)。wzp 需要保证倚天剑的心情在任意时刻不小于 0，否则他就会去搓衣板。
</p>
<p>
wzp 有 m 个大胆的想法，他猜想倚天剑初始时心情是 b[i]，由于他不想和搓衣板亲密接触，所以他决定根据倚天剑的心情来选择性的丢掉一些兵器。wzp 不舍得丢弃太多自己的兵器，现在他想知道对于他的每一个猜想，至少丢掉几件。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个数 n 和 m，表示 wzp 有的兵器个数和 wzp 的猜想个数。第二行 n 个数，代表 a[1]到 a[n]，wzp 的兵器会给倚天剑带来的心情变化。接下来 m 行为 m 个询问，代表了 wzp 所有大胆的想法，即倚天剑初始时的心情为 b[i]。询问互相独立。
</p>
<h3>
【输出格式】
</h3>
<p>
输出共 m 行，对每个 wzp 的大胆的想法，输出答案。
</p>
<h3>
【样例输入】
</h3>
<pre>6 3 
8 -5 -4 1 -7 4 
0
7
3
</pre>
<h3>
【样例输出】
</h3>
<pre>2 
0 
1
</pre>
<h3>
【提示】
</h3>
<p>
对于前 5%的数据，m=1;
</p>
<p>
对于另 5%的数据，所有 a[i]&lt;0
</p>
<p>
对于另 10%的数据，1≤n≤100，1≤m≤1000
</p>
<p>
对于前 30%的数据，1≤n≤500,1≤m≤100000
</p>
<p>
对于前 40%的数据, 1≤n≤750
</p>
<p>
对于前 60%的数据，1≤n≤2000
</p>
<p>
对于另 10%的数据，a[i]为随机生成对于
</p>
<p>
前 80%的数据，1≤n≤100000
</p>
<p>
对于 100%的数据，1≤n≤1000000  1≤m≤1000000  -10^9≤ai≤10^9  0≤bi≤10^15
</p>