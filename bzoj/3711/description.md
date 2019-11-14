
# Description

<div class="content"><p>体育课上，n个小朋友排成一行（从1到n编号），老师想把他们分成若干组，每一组都包含编号连续的一段小朋友，每个小朋友属于且仅属于一个组。<br/>
第i个小朋友希望它所在的组的人数不多于d[i]，不少于c[i]，否则他就会不满意。<br/>
在所有小朋友都满意的前提下，求可以分成的组的数目的最大值，以及有多少种分组方案能达到最大值。</p></div>

# Input

<div class="content"><p>第一行一个整数n(1&lt;=n&lt;=1000000)，表示小朋友的数目。<br/>
接下来n行，每行两个整数c[i],d[i](1&lt;=c[i]&lt;=d[i]&lt;=n)，表示i所在组的人数的最小值和最大值。</p></div>

# Output

<div class="content"><p>如果不存在这样的方案，仅输出一行NIE。<br/>
否则输出一行包含两个整数，组的数目的最大值、方案数量。（方案数量对1000000007取模）</p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1：<br/>
9<br/>
1 4<br/>
2 5<br/>
3 4<br/>
1 5<br/>
1 1<br/>
2 5<br/>
3 5<br/>
1 3<br/>
1 1<br/>
样例输入2：<br/>
2<br/>
1 1<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1:<br/>
5 2<br/>
样例输出2：<br/>
NIE<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

