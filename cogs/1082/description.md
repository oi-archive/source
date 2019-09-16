# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
<img src="/upload/image/20120927/20120927172603_67712.png" alt=""/> 
</p>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">圣诞节到了，FireDancer准备做一棵大圣诞树。左图为圣诞树的一个简单结构。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">这棵树被表示成一组被编号的结点和一些边的集合。结点从1到n编号。树的根永远是1。每个结点都有一个自身特有的数值，称为它的重。各个结点的重可能不同。对于一棵做完的树来说，每条边都有一个价值，若设这条边e连接结点i和结点j，且i为j的父结点(根是最老的祖先)，则该边的价值为(j的所有子孙及它自己的重之和)*（e的单位价值ce）。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">现在FireDancer想造一棵树，使得树上所有边的总价值最小，并且所有的点都在树上，因为FireDancer喜欢大树。</span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行两个整数n和m（0&lt;=n,m&lt;=50000），表示结点总数和可供选择的边数。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">下面一行有n个整数，依次表示每个结点的重。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">下面m行，每行有3个正整数a,b,c，表示结点a和结点b之间有一个单位价值为c的边可供你造树时选择。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入中的所有数都小于2^16。</span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">若无解，输出“No Answer”，否则一个整数表示造树的最小价值。</span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">[样例输入1]</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Chris.in</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2 1</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1 1</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1 2 15</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">[样例输入2]</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Chris.in</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">7 7</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">200 10 20 30 40 50 60</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1 2 1</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2 3 3</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2 4 2</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">3 5 4</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">3 7 2</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">3 6 3</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1 5 9</span> 
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<div>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">[样例输出1]</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">15</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">[样例输出2]</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1210</span> 
</p>
</div>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【来源】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;background-color:#003399;color:#FFE500;">江苏省常州市高级中学 曹文培训图论练习题</span> 
</p>
