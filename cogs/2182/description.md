# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">描述<br/>
zcwwzdjn在追杀十分sb的zhx，而zhx逃入了一个遥远的国度。当zcwwzdjn准备进入遥远的国度继续追杀时，守护神RapiD阻拦了zcwwzdjn的去路，他需要zcwwzdjn完成任务后才能进入遥远的国度继续追杀。</span> 
</p>
<p>
<span style="font-size:medium;">问题是这样的：遥远的国度有n个城市，这些城市之间由一些路连接且这些城市构成了一颗树。这个国度有一个首都，我们可以把这个首都看做整棵树的根，但遥远的国度比较奇怪，首都是随时有可能变为另外一个城市的。遥远的国度的每个城市有一个防御值，有些时候RapiD会使得某两个城市之间的路径上的所有城市的防御值都变为某个值。RapiD想知道在某个时候，如果把首都看做整棵树的根的话，那么以某个城市为根的子树的所有城市的防御值最小是多少。由于RapiD无法解决这个问题，所以他拦住了zcwwzdjn希望他能帮忙。但zcwwzdjn还要追杀sb的zhx，所以这个重大的问题就被转交到了你的手上。</span> 
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">第1行两个整数n m，代表城市个数和操作数。<br/>
第2行至第n行，每行两个整数 u v，代表城市u和城市v之间有一条路。<br/>
第n+1行，有n个整数，代表所有点的初始防御值。<br/>
第n+2行一个整数 id，代表初始的首都为id。<br/>
第n+3行至第n+m+2行，首先有一个整数opt，如果opt=1，接下来有一个整数id，代表把首都修改为id；如果opt=2，接下来有三个整数p1 p2 v，代表将p1 p2路径上的所有城市的防御值修改为v；如果opt=3，接下来有一个整数 id，代表询问以城市id为根的子树中的最小防御值。<br/>
</span> 
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
<br/>
<span style="font-size:medium;">对于每个opt=3的操作，输出一行代表对应子树的最小点权值。<br/>
</span> 
</p>
</div>
<h3>
【样例输入】
</h3>
<p>
</p><p>
 3 7
</p>
<p>
 1 2
</p>
<p>
 1 3
</p>
<p>
 1 2 3
</p>
<p>
 1
</p>
<p>
 3 1
</p>
<p>
 2 1 1 6
</p>
<p>
 3 1
</p>
<p>
 2 2 2 5
</p>
<p>
 3 1
</p>
<p>
 2 3 3 4
</p>
<p>
 3 1
</p>
<p></p>
<h3>
【样例输出】
</h3>
<p>
</p><p>
 1
</p>
<p>
 2
</p>
<p>
 3
</p>
<p>
 4
</p>
<p>
 提示
</p>
<p>
 对于20%的数据，n&lt;=1000 m&lt;=1000。 对于另外10%的数据，n&lt;=100000，m&lt;=100000，保证修改为单点修改。 对于另外10%的数据，n&lt;=100000，m&lt;=100000，保证树为一条链。 对于另外10%的数据，n&lt;=100000，m&lt;=100000，没有修改首都的操作。 对于100%的数据，n&lt;=100000，m&lt;=100000，0&lt;所有权值&lt;=2^31。
</p>
<p></p>
<h3>
【提示】
</h3>
<div class="content">
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search=zhonghaoxi提供">zhonghaoxi提供</a>  （stone添加 ID:3327）
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=3083">耒阳大世界（衡阳八中） OJ 3083</a>
