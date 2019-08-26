
# Description

<div class="content"><div>你应该知道，什么是最大公约数：对于任意两个非零整数x，y，若整数d能同时被x和y整除，则称d为x与y的公约数</div>
<div>。定义x与y的最大公约数gcd(x, y)为x与y的最大的公约数。如gcd(6, 9) = 3，gcd(12, 16) = 4，gcd(25, 32) =</div>
<div> 1，等等。这里，我们定义什么是幸运数：对于一个正整数d，我们使用di表示d在十进制表示下，按从低位到高位</div>
<div>顺序的第i位数字。设F(d)表示d的奇数位的数字之和，即F(d) = d1 + d3 + d5 + ……；设G(d)表示d的偶数位的</div>
<div>数字之和，即G(d) = d2 + d4 + d6 + ……；若F(d)与G(d)均大于0，且F(d)与G(d)的最大公约数不超过K，则称d</div>
<div>为幸运数。其中K是一个已知的常数。举个例子来说，若d = 641，则d1 = 1，d2 = 4，d3 = 6，F(641) = 1 + 6 =</div>
<div> 7，G(641) = 4。此时F(d)与G(d)的最大公约数即gcd(7, 4)等于1。则当K不小于1时641是幸运数。请你回答下面</div>
<div>的问题：对于给定的K，在不小于L并且不超过R的所有整数中，有多少个数是幸运数？注意，输入文件包含多组测</div>
<div>试数据。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数T，表示有T组测试数据。</div>
<div>接下来T行，每行包含三个整数K、L、R，表示一次询问。</div>
<p></p></div>

# Output

<div class="content"><div>输出T行，每行一个整数，依次表示每组测试数据的答案。</div>
<div>1 ≤ L ≤ R ≤ 10^18， 1 ≤ K ≤ 10^2，1 ≤ T ≤ 1000</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 1 10<br/>
2 28 34<br/>
100 987654321 987654321<br/>
1 1 50000<br/>
1 50001 100000</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
5<br/>
1<br/>
30298<br/>
30309<br/>
【样例解释】<br/>
K = 1时，1到10之间不存在幸运数。<br/>
K = 2时，28到34之间的幸运数有28、29、31、32、34，共5个。<br/>
K = 100时，987654321是幸运数。<br/>
K = 1时，1到50000之间的幸运数有30298个，50001到100000之间的幸运数有30309个。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

