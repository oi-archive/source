
# Description

<div class="content"><p>像他的祖先一样，Mansur喜欢繁殖马匹。目前，他拥有哈萨克斯坦最大的马场。以前情况可不是这样，N年前Mansur年轻时，他只拥有一匹马，但他一直梦想着成为富豪，最终,他美梦成真。<br/>
按照时间的先后顺序将年份编号为0到N-1（即N-1年是最近的一年）。每年的天气会影响马匹的繁殖。Mansur用一个正整数X[i]记录第i年的繁殖系数，如果第i年开始时有h匹马，那么这一年结束时会有h•X[i]匹马。<br/>
每年，只有年底的时候可以出售马匹。Mansur用一个正整数Y[i]记录第i年末卖出一匹马的售价。Mansur可以卖出任意多匹马，每匹售价均为Y[i]。<br/>
现在，Mansur想知道如果在N年中，他总能在最佳时间出售马匹，他能获得的最⼤收益是多少？你正好在Mansur家做客，所以他想请你帮他回答这个问题。<br/>
Mansur对记录下的X和Y做了M次更新，每次更新，Mansur要么改变一个X[i] ，要么改变一个Y[i]。每次更新后，他都会问你出售马匹能获得的最大收益。Mansur的更新是累加的，即你的每个回答时都应该考虑之前的所有更新。注意：某个X[i]或者Y[i]可能会被更新多次。<br/>
对于Mansur的问题，实际的答案可能是一个非常大的数字，你只要给出实际答案模10^9+7后的结果即可。</p></div>

# Input

<div class="content"><p>第1行: N<br/>
第2行: X[0] … X[N - 1]<br/>
第3行: Y[0] … Y[N - 1]<br/>
第4行: M<br/>
第5,…,M+4行: 每行3个数字type pos val (type=1表示updateX，type=2 表<br/>
示updateY)。<br/>
N: 表示总共有N年。<br/>
X: 长度为N的数组，对0≤i≤N-1,X[i]表示i年的繁殖系数。<br/>
Y: 长度为N的数组，对0≤i≤N-1,Y[i]表示i年末出售一匹马的价格。<br/>
注意：X、Y均为Mansur给定的初值（更新前的值）。<br/>
pos: 一个整数，范围是0，…,N-1。<br/>
val: X[pos]或Y[pos]更新后的值。</p></div>

# Output

<div class="content"><p>共M+1行<br/>
第1行：一个整数表示初始状态下，Mansur获得的最大收益模10^9+7后的值。<br/>
第2,…,M+1行：每行一个整数，表示这次更新后Mansur获得的最大收益模10^9+7后的值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 1 3<br/>
3 4 1<br/>
1<br/>
2 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢yts1999上传">鸣谢yts1999上传</a></p></div>

