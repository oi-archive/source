# 题目描述


<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个边长为<span>n</span><span>的正三角形可以被划分成若干个小的边长为</span><span>1</span><span>的正三角形，称为单位三</span></span><span style="font-family:宋体;font-size:10.5pt;">角形。<img src="/upload/image/20121017/20121017085930_11333.png" alt="" align="right" height="124" width="134"/><span></span></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-family:宋体;font-size:10.5pt;">如右图，边长为</span><span style="font-family:宋体;font-size:10.5pt;">3</span><span style="font-family:宋体;font-size:10.5pt;">的正三角形被分成三层共</span><span style="font-family:宋体;font-size:10.5pt;">9</span><span style="font-family:宋体;font-size:10.5pt;">个小的正三角形，我们把它们从顶到</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">底，从左到右以1～9编号，见右图。同理，边长为n的正三角形可以划分成n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:super;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">个单位三</span><span style="font-family:宋体;font-size:10.5pt;">角形。</span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">四个这样的边长为<span>n</span><span>的正三角形可以组成一个三棱锥。我们将正三棱锥的三个侧面依</span></span><span style="font-family:宋体;font-size:10.5pt;">顺时针次序（从顶向底视角）编号为</span><span style="font-family:宋体;font-size:10.5pt;">A, B, C</span><span style="font-family:宋体;font-size:10.5pt;">，底面编号为</span><span style="font-family:宋体;font-size:10.5pt;">D</span><span style="font-family:宋体;font-size:10.5pt;">。侧面的</span><span style="font-family:宋体;font-size:10.5pt;">A, B, C</span><span style="font-family:宋体;font-size:10.5pt;">号三角形以</span><span style="font-family:宋体;font-size:10.5pt;">三棱锥的顶点为顶，底面的</span><span style="font-family:宋体;font-size:10.5pt;">D</span><span style="font-family:宋体;font-size:10.5pt;">号三角形以它与</span><span style="font-family:宋体;font-size:10.5pt;">A</span><span style="font-family:宋体;font-size:10.5pt;">，</span><span style="font-family:宋体;font-size:10.5pt;">B</span><span style="font-family:宋体;font-size:10.5pt;">三角形的交点为顶。左图为三棱锥展</span><span style="font-family:宋体;font-size:10.5pt;">开后的平面图，每个面上标有圆点的是该面的顶，该图中侧面</span><span style="font-family:宋体;font-size:10.5pt;">A, B, C</span><span style="font-family:宋体;font-size:10.5pt;">分别向纸内方向折</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">叠即可还原成三棱锥。我们把这A，B、C、D四个面各自划分成n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:super;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">个单位三角形。</span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">  </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> <img src="/upload/image/20121017/20121017090002_26124.png" alt="" align="left" height="156" width="178"/><span></span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">对于任意两个单位三角形，如有一条边相邻，则称它们为相邻的单位三角形。显然，每个单位三角形有三个相邻的单位三角形。现在，把<span>1</span><span>—</span><span>4n2</span><span>分别随机填入四个面总共</span><span>4n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:super;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">个单位三角形中。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    现在要求你编程求</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">由单位三角形组成的最大排序二叉树</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。所谓最大排序二叉树，是指在所有由单位三角形组成的排序二叉树中节点最多的一棵树．对于任一单位三角形，可选它三个相邻的单位三角形中任意一个作为父节点，其余两个分别作为左孩子和右孩子。当然，做根节点的单位三角形不需要父节点，而左孩子和右孩于对于二叉树中的任意节点来说并不是都必须的。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    输入文件为bs<span>tree.in</span><span>。其中第一行是一个整数</span><span>n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">=n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">=18</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，随后的<span>4n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:super;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">个数，依次为三棱锥四个面上所填的数字。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出文件为bs<span>tree.out</span><span>。其中仅包含一个整数，表示最大的排序二又树所含的节点数目。</span></span> 
</p>
<h3>
【样例输入】
</h3>
<pre><p>
3
</p>

<p>
19 33 32 31 29 3 5 4 30
</p>

<p>
22 24 20 21 12 24 23 34 35
</p>

<p>
14 13 15 26 18 17 8 16 27
</p>

<p>
11 10 9 1 28 7 2 6 36
</p>
</pre>
<p>
<span style="font-weight:bold;font-size:10.5pt;font-family:宋体;">【样例】</span><span style="font-weight:bold;font-size:10.5pt;font-family:宋体;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5pt;font-family:宋体;"></span><span style="font-size:10.5pt;font-family:宋体;">输入文件对应下图：</span><span style="font-size:10.5pt;font-family:宋体;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:宋体;"><img src="/upload/image/20121017/20121017090120_41691.png" alt="" height="120" width="550"/><br/>
</span> 
</p>
<h3>
【样例输出】
</h3>
<pre>17</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
输出样例文件对应的最大排序二叉树如下图所示：
</p>
<p>
<img src="/upload/image/20121017/20121017090156_57994.png" alt=""/> 
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
