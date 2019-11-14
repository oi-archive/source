
# Description

<div class="content">CICI和PG斗牛，他们都是牛人，所以把所有的技术指标归结到四个能力：2分球、3分球、抢断和防守。我们用pt2(1), pt3(1), reb(1)和def(1)来描述CICI的这4种能力，并用pt2(2), pt3(2), reb(2)、def(2)来描述PG。每种能力都是一个1~10的整数。
	比赛中经过统计两人都遵守以下的规则：

1. CICI选择投3分球的概率为pt3(1)/[pt3(1)+pt2(1)], 否则他将投2分。
2.如果CICI投3分球，那么他进球的概率为0.8*pt3(1)/[pt3(1)+def(2)], 否则就丢球了。
3.如果CICI投2分球，那么他进球的概率为pt2(1)/[pt2(1)+def(2)], 否则他丢球。 
4.如果CICI丢球了，他将球重新抢回来的概率为0.8*reb(1)/[reb(1)+reb(2)], 否则球权归PG。

对于PG规则也是和上面类似的。

一场比赛如果谁先得到N分或者高于N分，那么谁获胜，初始时CICI得球。经过CICI的多年观察，他已经对PG的技术参数了如指掌了，现在他要调整自己的技术参数（因为某种原因导致他所有的参数总和必须为M），使得他自己获胜的概率最大，但是他又懒得算了，请你帮忙。

</div>

# Input

<div class="content">一行6个数代表一组数据，6个数分别是N, M, pt2(2), pt3(2), reb(2), def(2)。
数据读到文件末尾。

</div>

# Output

<div class="content">每行一个实数代表最大获胜概率，精确到小数点后5位。

</div>

# Sample Input

<div class="content"><span class="sampledata">4 29 8 3 5 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.79961<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p>数据组数小于等于10。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

