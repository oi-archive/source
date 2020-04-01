
# Description

<div class="content"><p><a href="/JudgeOnline/upload/201105/file/cc.jpg"><img alt="" src="/source/bzoj/2307/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNS9pbWFnZS9jYy5qcGc=.jpg"/></a></p></div>

# Input

<div class="content"><p>第一行包括三个由空格隔开的非负整数 n、m1、m2。 从第 2行到第m1 + 1 行，每行有三个正整数x、y、d，表示(1, x)与(1, y)之间有一条权值为d的边。 <br/>
从第 m1 + 2 行到第 m1 + m2 + 1 行，每行有三个正整数x、y、d，表示(1, x)<br/>
与(2, y)之间有一条权值为 d的边。 <br/>
每行的三个整数之间都用一个空格隔开。 图中两个点x 和 y之间可能有多于<br/>
1条边连接，一条边连接的两个节点可能相同。</p></div>

# Output

<div class="content"><p>只有一行，包含一个实数，即所有桥的权值之和，四舍五入保留两位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】 <br/>
3 1 3 <br/>
1 2 4 <br/>
1 2 5 <br/>
2 3 3 <br/>
3 3 1 <br/>
【样例输出1】 <br/>
1.00 <br/>
【样例说明1】 <br/>
这就是问题描述中所举的例子。 <br/>
<br/>
【样例输入2】 <br/>
1 1 1 <br/>
1 1 100 <br/>
1 1 1 <br/>
【样例输出2】 <br/>
10.00 </span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p>数据编号       n                            m1                        m2 <br/><br/>
1                   ≤ 10                  ≤ 50                     ≤ 50 <br/><br/>
2                  ≤ 10 000          ≤ 40 000              ≤ 40 000 <br/><br/>
3                 ≤ 300 000         ≤ 500 000               = 1 <br/><br/>
4~7            ≤ 300 000          ≤ 500 000           ≤ 500 <br/><br/>
8~10         ≤ 300 000          ≤ 500 000           ≤ 500 000</p><br/>
<p></p><br/>
<p>100%的数据中，d ≤ 100。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

