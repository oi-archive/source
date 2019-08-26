
# Description

<div class="content">
	
一个矩阵由r行c列共r*c个小正方形组成。行从下到上编号为1到r，列从左到右编号为1到c。所有坐标都是(row,colmn)的形式。
给出n个特殊点的坐标，保证特殊点在矩阵内，依次编号为1到n，从(1,1)到(r,c)的包含严格k个特殊点的路径称为k型路径。
同时路径必须遵循以下规则：
1.	每次你只能向上或向右。即你只能从(x,y)走到(x+1,y)或(x,y+1)
2.	特殊点在路径中出现的顺序必须与给出的顺序相同，即如果特殊点a出现在特殊点b之前，那么a必须小于b。
请输出0型路径，1型路径…,n型路径的条数mod 1000007
</div>

# Input

<div class="content">第一行两个数R,C。
第二行描述1-n号特殊点的行号。请读到行尾。
第二行描述1-n号特殊点的列号。

</div>

# Output

<div class="content">N+1个用空格隔开的整数，分别表示1型路径…,n型路径的条数mod 1000007

</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3<br/>
2 3<br/>
2 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 3 2<br/>
<br/>
【样例解释】<br/>
0型路径<br/>
(1, 1) -&gt; (1, 2) -&gt; (1, 3) -&gt; (2, 3) -&gt; (3, 3)<br/>
1型路径<br/>
(1, 1) -&gt; (2, 1) -&gt; (2, 2) -&gt; (2, 3) -&gt; (3, 3)<br/>
(1, 1) -&gt; (1, 2) -&gt; (2, 2) -&gt; (2, 3) -&gt; (3, 3)<br/>
(1, 1) -&gt; (2, 1) -&gt; (3, 1) -&gt; (3, 2) -&gt; (3, 3)<br/>
2型路径<br/>
(1, 1) -&gt; (2, 1) -&gt; (2, 2) -&gt; (3, 2) -&gt; (3, 3)<br/>
(1, 1) -&gt; (1, 2) -&gt; (2, 2) -&gt; (3, 2) -&gt; (3, 3)<br/>
<br/>
【数据规模】<br/>
对于100%数据<br/>
1&lt;=R,C&lt;=50<br/>
0&lt;=N&lt;=50<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

