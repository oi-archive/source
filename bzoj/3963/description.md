
# Description

<div class="content"><div>你是任意性复杂机器公司(Arbitrarily Complex Machines, ACM)的经理，公司使用更加先进的机械设备生产先进的机器。原来的那一台生产机器已经坏了，所以你要去为公司买一台新的生产机器。你的任务是在转型期内尽可能得到更大的收益。在这段时间内，你要买卖机器，并且当机器被ACM公司拥有的时候，操控这些机器以获取利润。因为空间的限制，ACM公司在任何时候都只能最多拥有一台机器。</div>
<div>在转型期内，有若干台可能卖出的机器。作为先进机器的专家，对于每台机器Mi，你已经知道了其价格Pi和可以买入的日期Di。注意，如果不在第Di天买入机器Mi，那么别的人也会买走这一台机器，也就是说，以后你将没有机会购买这台机器了。如果ACM的钱低于一台机器的价格，那么你显然不可能买到这一台机器。</div>
<div>如果你在第Di天买入了机器Mi,那么ACM公司可以从第(Di)+1天开始使用这一台机器。每使用这台机器一天，就可以为公司创造出Gi美元的收益。</div>
<div>你可以决定要在买入之后的某一天，以一定的折扣价卖出这一台机器。收购市场对于每一台机器，都有一个折扣价Ri。你不能在卖出的那一天使用机器，但是你可以在卖出的那一天再买入一台新的。</div>
<div>在转型期结束后，ACM公司会卖掉当前所拥有的机器。你的任务就是最大化转型期间ACM公司可以得到的收入。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入包含若干组测试用例。每一组测试用例的第一行有3个正整数N，C和D。N是将会卖出的机器的台数(N&lt;=10^5)，C是在转型期开始时公司拥有的美元数量(C&lt;=10^9)，D是转型期持续的天数(D&lt;=10^9)。</div>
<div>之后的N行每一行描述了一台机器的情况。每一行有4个正整数Di,Pi,Ri和Gi,分别表示这台机器卖出的时间，购买这台机器需要的美元数量，卖出这台机器的折扣价和使用这台机器可以得到的利润。这些数字满足1&lt;=Di&lt;=D,1&lt;=Ri&lt;Pi&lt;=10^9且1&lt;=Gi&lt;=10^9.</div>
<div>最后一组测试用例后面的一行由3个0组成，表示输入数据。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每一组测试用例，输出测试用例的编号，之后给出ACM公司在第D+1天结束后可以得到的最大数量的美元。</div>
<div>
<div>请依照下面给出的样例输出。</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 10 20<br/>
6 12 1 3<br/>
1 9 1 2<br/>
3 2 1 2<br/>
8 20 5 4<br/>
4 11 7 4<br/>
2 10 9 1<br/>
0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 44</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

