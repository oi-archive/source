
# Description

<div class="content"><div>对于一个区间集合{A1,A2……AK}(K&gt;1，Ai&lt;&gt;Aj{i&lt;&gt;j})，我们定义其权值</div>
<div>W=|A1∪A2∪……∪AK|*|A1∩A2∩……AK|当然，如果这些区间没有交集则权值为0。</div></div>

# Input

<div class="content"><div>给你N个（1&lt;N&lt;=10^6）各不相同的区间，请你从中找出若干个区间使其权值最大。</div>
<div>第一行N,接下来N行 l r(1&lt;=l&lt;r&lt;=10^6)</div></div>

# Output

<div class="content"><p>最大权值</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 6<br/>
4 8<br/>
2 7<br/>
3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">24<br/>
样例注释:选择第1个和第3个区间,交为(2,6),并为(1,7),权值为4*6=24.<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-family: arial, verdana, helvetica, sans-serif; text-align: -webkit-center;"><br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢alone_wolf修正数据--2017.6.22">鸣谢alone_wolf修正数据--2017.6.22</a></p></div>

