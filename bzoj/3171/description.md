
# Description

<div class="content"><div class="panel-body"><span style="font-size: medium;">一个循环格就是一个矩阵，其中所有元素为箭头，指向相邻四个格子。每个元素有一个坐标（行，列），其中左上角元素坐标为（0,0）。给定一个起始位置（r，c）<br/>
</span>
<p><span style="font-size: medium;"> ，你可以沿着箭头防线在格子间行走。即如果（r,c）是一个左箭头，那么走到（r，c-1）;如果是右箭头那么走到（r，c+1）；如果是上箭头那么走到（r-1，c）；如果是下箭头那么走到（r+1，c）；每一行和每一列都是循环的，即如果走出边界，你会出现在另一侧。<br/>
一个完美的循环格是这样定义的：对于任意一个起始位置，你都可以i沿着箭头最终回到起始位置。如果一个循环格不满足完美，你可以随意修改任意一个元素的箭头直到完美。</span><span style="font-size: medium;">给定一个循环格，你需要计算最少需要修改多少个元素使其完美。</span></p>
</div>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行两个整数R，C。表示行和列，接下来R行，每行C个字符LRUD，表示左右上下。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一个整数，表示最少需要修改多少个元素使得给定的循环格完美</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
RRRD<br/>
URLL<br/>
LRRR</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium;">1&lt;=R,L&lt;=15</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

