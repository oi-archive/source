
# Description

<div class="content"><div>HarryPotter是一家游乐场的新负责人。刚上任时HarryPotter发现游客们频频抱怨 游乐场的道路非常拥挤。经过</div>
<div>研究，HarryPotter打算把游乐场中所有道路改为单行道， 就是说游客只能从道路的一端走到另一端，而反过来不</div>
<div>行。但是新的问题出现了：如何 保证游客能从公园的任意一个的地方走到任意其他地方。由于游乐场的道路错综</div>
<div>复杂， HarryPotter花了很长时间也没找到道路更改的方案。 整个游乐场可以看作是由n个区域和m个连接两区域</div>
<div>的道路组成的。任意两个不同的 区域间至多有一条道路。请你帮助HarryPotter将所有道路设为单向，并且使游客</div>
<div>能从 任意区域到达任何他想去的区域。</div></div>

# Input

<div class="content"><div>
<div>第一行有2个整数n,m。n为游乐场被的区域数，m为道路数。</div>
<div>以下有m行，每行有两个整数i,j。表示区域i与区域j之间有一条道路。 </div>
<div>规模：0 &lt; n  &lt; = 100</div>
</div>
<div></div></div>

# Output

<div class="content"><div>如果没有可行方案就输出&#34;impossible&#34;，</div>
<div>否则： 输出m行，每行有两个整数i,j，表示区域i与区域j之间的道路方向为从i到j。 </div>
<div>注意：输出数据描述的道路必须与输入数据吻合。</div>
<div>也就是说对于输入数据中的每一 组i,j，一定能在输出数据件中找到i,j或j,i。</div></div>

# Sample Input

<div class="content"><span class="sampledata">输入样例1<br/>
3 3<br/>
1 2<br/>
1 3<br/>
2 3<br/>
输入样例2<br/>
4 3<br/>
1 2<br/>
2 3<br/>
3 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">输出样例1<br/>
1 2<br/>
2 3<br/>
3 1<br/>
<br/>
输出样例2<br/>
impossible</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢vfleaking提供Spj">鸣谢vfleaking提供Spj</a></p></div>

