
# Description

<div class="content"><div><span>     </span>有n个城市(编号从0..n-1)，m条公路(双向的)，从中选择n-1条边，使得任意的两个城市能够连通，一条边需要的c的费用和t的时间，定义一个方案的权值v=n-1条边的费用和*n-1条边的时间和，你的任务是求一个方案使得v最小</div></div>

# Input

<div class="content"><div style="text-indent: 20.25pt">第一行两个整数n,m,接下来每行四个整数a,b,c,t,表示有一条公路从城市a到城市b需要t时间和费用c</div></div>

# Output

<div class="content"><div>【output】timeismoney.out</div>
<div style="text-indent: 21pt">仅一行两个整数sumc，sumt,（sumc表示使得v最小时的费用和，sumc表示最小的时间和） 如果存在多个解使得sumc*sumt相等，输出sumc最小的</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
0 1 161 79<br/>
0 2 161 15<br/>
0 3 13 153<br/>
1 4 142 183<br/>
2 4 236 80<br/>
3 4 40 241<br/>
2 1 65 92<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">279 501<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据规模】<br/><br/>
1&lt;=N&lt;=200<br/><br/>
1&lt;=m&lt;=10000<br/><br/>
0&lt;=a,b&lt;=n-1<br/><br/>
0&lt;=t,c&lt;=255<br/><br/>
有5%的数据m=n-1<br/><br/>
有40%的数据有t=c<br/><br/>
对于100%的数据如上所述</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

