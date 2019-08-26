
# Description

<div class="content"><p>维护一个W*W的矩阵，初始值均为S.每次操作可以增加某格子的权值,或询问某子矩阵的总权值.修改操作数M&lt;=160000,询问数Q&lt;=10000,W&lt;=2000000.</p></div>

# Input

<div class="content"><p>第一行两个整数,S,W;其中S为矩阵初始值;W为矩阵大小<br/>
<br/>
接下来每行为一下三种输入之一(不包含引号):<br/>
<br/>
&#34;1 x y a&#34;<br/>
<br/>
&#34;2 x1 y1 x2 y2&#34;<br/>
<br/>
&#34;3&#34;<br/>
<br/>
输入1:你需要把(x,y)(第x行第y列)的格子权值增加a<br/>
<br/>
输入2:你需要求出以左下角为(x1,y1),右上角为(x2,y2)的矩阵内所有格子的权值和,并输出<br/>
<br/>
输入3:表示输入结束</p></div>

# Output

<div class="content"><p>对于每个输入2,输出一行,即输入2的答案</p></div>

# Sample Input

<div class="content"><span class="sampledata">0 4<br/>
1 2 3 3<br/>
2 1 1 3 3<br/>
1 2 2 2<br/>
2 2 2 3 4<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
5</span></div>

# Hint

<div class="content"><p></p><p>保证答案不会超过int范围</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

