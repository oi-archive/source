
# Description

<div class="content"><div>某列火车行使在C个城市之间(出发的城市编号为1，结束达到的城市的编号为C)，假设该列火车有S个座位，现在有</div>
<div>R笔预订票的业务。现在想对这R笔业务进行处理，看哪些预定能满足，哪些不能满足。一笔预定由O、D、N三个整</div>
<div>数组成，表示从起点站O到目标站D需要预定N个座位。一笔预定能满足是指该笔业务在行程范围内有能满足的空座</div>
<div>位，否则就不能满足。一笔业务不能拆分，也就是起点和终点站不能更改，预定的座位数目也不能更改。所有的预</div>
<div>定需求按给出先后顺序进行处理。请你编写程序，看那些预定业务能满足，那些不能满足。</div></div>

# Input

<div class="content"><div>第一行为三个整数C、S、R，(1&lt;=c&lt;=60 000, 1&lt;=s&lt;=60 000, 1&lt;=r&lt;=60 000)他们之间用空隔分开。</div>
<div>接下来的S行每行为三个整数O、D、N，(1&lt;=o&lt;d&lt;=c, 1&lt;=n&lt;=s)，分别表示每一笔预定业务。</div></div>

# Output

<div class="content"><div>
<div>对第I笔业务，如果能满足，则在输出输出“T”，否则输出“F”</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 6 4<br/>
1 4 2<br/>
1 3 2<br/>
2 4 3<br/>
1 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">T<br/>
T<br/>
N<br/>
N</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

