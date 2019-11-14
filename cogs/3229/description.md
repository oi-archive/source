# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<div>
  给定一棵树，边的颜色为黑或白，初始时全部为白色。维护两个操作：
</div>
<div>
  1.查询 $u$ 到根路径上的第一条黑色边的标号。
</div>
<div>
  2.将 $u$ 到 $v$ 路径上的所有边的颜色设为黑色。
</div>
<div>
  Notice:这棵树的根节点为1
</div>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<div>
<div>
<div>
  第一行两个数n,m分别表示点数和操作数。
</div>
<div>
  接下来n-1行，每行2个数$u,v$.表示一条 $u$ 到 $v$ 的边。
</div>
<div>
  接下来m行，每行为以下格式：
</div>
<div>
  1 v 表示第一个操作
</div>
<div>
  2 v u 表示第二种操作
</div>
<div>
 $ n，m&lt;=10^6$
</div>
</div>
</div>
</div>
<h3>
【输出格式】
</h3>
<p>
对于每个询问，输出相应答案。
</p>
<p>
如果不存在，输出0
</p>
<h3>
【样例输入】
</h3>
<p>
5 4
</p>
<p>
1 2
</p>
<p>
1 3
</p>
<p>
2 4
</p>
<p>
2 5
</p>
<p>
1 2
</p>
<p>
2 2 3
</p>
<p>
1 3
</p>
<p>
1 4
</p>
<h3>
【样例输出】
</h3>
<p>
 0 
</p>
<p>
 2 
</p>
<p>
 1
</p>
<h3>
【提示】
</h3>
<h3>
【来源】
</h3>
<div class="content">
<p>
BZOJ 3319<a href="problemset.php?search="></a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=3319">耒阳大世界（衡阳八中） OJ 3319</a>
