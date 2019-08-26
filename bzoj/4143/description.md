
# Description

<div class="content"><div>Byteasar要制订m天的会议计划，一共有n场会议，第i场会议开始于第d[i]天的第a[i]秒，结束于第d[i]天的第b[i]秒。</div>
<div>对于每一天，请找出这一天的两场会议i,j，使得它们不冲突，即不存在一个数k同时满足a[i]&lt;=k&lt;=b[i]以及a[j]&lt;=k&lt;=b[j]。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(2&lt;=n&lt;=500000,1&lt;=m&lt;=20)，表示会议的场数和天数。</div>
<div>接下来n行，每行包含三个正整数a[i],b[i],d[i](1&lt;=a[i]&lt;b[i]&lt;=80000000,1&lt;=d[i]&lt;=m)，描述一场会议。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出m行。第i行输出第i天的答案，如果无解，输出NIE，否则输出TAK,然后输出这一天参加的两场会议的编号，</div>
<div>如有多组解，输出任意一组。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
3 5 1<br/>
2 4 2<br/>
1 8 1<br/>
6 7 3<br/>
3 5 2<br/>
7 12 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK 1 6<br/>
NIE<br/>
NIE</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

