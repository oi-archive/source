
# Description

<div class="content"><p><span id="1386076052352S" style="display: none"> </span><span style="font-size: medium"><font face="Times New Roman">给定一棵大小为 n 的有根点权树,支持以下操作: <br/>
　　• 换根 <br/>
　　• 修改点权  <br/>
    　• 查询子树最小值 <br/>
</font></span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">　　第一行两个整数 n, Q ,分别表示树的大小和操作数。 <br/>
　　接下来n行,每行两个整数f,v,第i+1行的两个数表示点i的父亲和点i的权。保证f &lt; i。如 果f = 0,那么i为根。输入数据保证只有i = 1时,f = 0。 <br/>
　　接下来 m 行,为以下格式中的一种: <br/>
　　• V x y表示把点x的权改为y <br/>
　　• E x 表示把有根树的根改为点 x <br/>
　　• Q x 表示查询点 x 的子树最小值 <br/>
</font></span></p>
<p><span id="1386076052487E" style="display: none"> </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">　　对于每个 Q ,输出子树最小值。 <br/>
</font></span></p>
<p align="left"></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 7<br/>
0 1<br/>
1 2<br/>
1 3<br/>
Q 1<br/>
V 1 6<br/>
Q 1<br/>
V 2 5<br/>
Q 1<br/>
V 3 4<br/>
Q 1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
<br/>
1<br/>
2<br/>
3<br/>
4<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>　　对于 100% 的数据:n, Q ≤ 10^5。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

