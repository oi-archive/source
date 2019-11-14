
# Description

<div class="content"><div>农夫John准备扩大他的农场,他正在考虑N (1 &lt;= N &lt;= 50,000) 块长方形的土地. 每块土地的长宽满足(1 &lt;= 宽 &lt;</div>
<div>= 1,000,000; 1 &lt;= 长 &lt;= 1,000,000). 每块土地的价格是它的面积,但FJ可以同时购买多快土地. 这些土地的价</div>
<div>格是它们最大的长乘以它们最大的宽, 但是土地的长宽不能交换. 如果FJ买一块3x5的地和一块5x3的地,则他需要</div>
<div>付5x5=25. FJ希望买下所有的土地,但是他发现分组来买这些土地可以节省经费. 他需要你帮助他找到最小的经费.</div></div>

# Input

<div class="content"><div>* 第1行: 一个数: N</div>
<div>* 第2..N+1行: 第i+1行包含两个数,分别为第i块土地的长和宽</div></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第一行: 最小的可行费用. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
100 1<br/>
15 15<br/>
20 5<br/>
1 100<br/>
输入解释:<br/>
共有4块土地.</span></div>

# Sample Output

<div class="content"><span class="sampledata">500<br/>
FJ分3组买这些土地: <br/>
第一组:100x1, <br/>
第二组1x100, <br/>
第三组20x5 和 15x15 plot.<br/>
每组的价格分别为100,100,300, 总共500.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

