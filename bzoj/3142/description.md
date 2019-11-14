
# Description

<div class="content"><p><span style="font-size: medium">小T最近在学着买股票，他得到内部消息：F公司的股票将会疯涨。股票每天的价格已知是正整数，并且由于客观上的原因，最多只能为N。在疯涨的K天中小T观察到：除第一天外每天的股价都比前一天高，且高出的价格（即当天的股价与前一天的股价之差）不会超过M，M为正整数。并且这些参数满足M(K-1)&lt;N。<br/>
小T忘记了这K天每天的具体股价了，他现在想知道这K天的股价有多少种可能</span></p></div>

# Input

<div class="content"><p><font size="4">只有一行用空格隔开的四个数：N、K、M、P。对P的说明参见后面“输出格式”中对P的解释。<br/>
输入保证20%的数据M,N,K,P≤20000，保证100%的数据M,K,P≤109，N≤1018 。</font></p></div>

# Output

<div class="content"><p><font size="4">仅包含一个数，表示这K天的股价的可能种数对于P的模值。【输入输出样例】<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">7  3 2 997             </span></div>

# Sample Output

<div class="content"><span class="sampledata">16<br/>
【样例解释】<br/>
输出样例的16表示输入样例的股价有16种可能：<br/>
{1，2，3}，{1，2，4}，{1，3，4}，{1，3，5}， {2，3，4}，{2，3，5}，{2，4，5}，{2，4，6}， {3，4，5}，{3，4，6}，{3，5，6}，{3，5，7}，{4，5，6}，{4，5，7}，{4，6，7}，{5，6，7}</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

