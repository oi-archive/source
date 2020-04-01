
# Description

<div class="content"><div>
<div>有一个长度为N的数组Ai，每个元素可以取1~M中的一个正整数。那么一共有M^N种可能的数组。因为 SHUXK 对数</div>
<div>论有特殊的爱好，所以他立刻想到了下面两个问题：</div>
<div>1. 对于给定的正整数K，有多少个数组Ai满足GCD(A1,A2...An) = K</div>
<div>2. 对于给定的正整数K，有多少个数组Ai满足K|Lcm(A1,A2...An)</div>
<div>（我相信机智的你在看到这道题的英文名称时就已经猜得八九不离十了）当然，对于 SHUXK 来说，只询问一个K的</div>
<div>情况很简单。于是他加强了一下：给定一个范围L~R，对L~R中所有的正整数K都求出答案，并且把它们加起来作为</div>
<div>最终的结果。然后， SHUXK 就不会了……他需要你来帮助他计算出答案。 由于答案可能很大，我们只要求输出答</div>
<div>案对1,000,000,007取模的结果。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行包含两个正整数T和Type，分别表示测试数据的组数和数据类型</div>
<div>（ Type = 1时只询问 gcd 的问题， Type = 2时只询问 lcm 的问题）。</div>
<div>以下T行，每行包含四个正整数N,M,L,R（ 1 ≤ L ≤ R≤ M），含义如题面所述。</div>
<div>T&lt;=500，Type=1时，M&lt;=10^7，Type=2时M&lt;=1000</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出文件应包含T行，每行输出一个整数，表示一组测试数据的答案对</div>
<div>1,000,000,007取模的结果。答案的顺序应与输入数据的顺序保持一致。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 1<br/>
5 5 1 5<br/>
5 5 2 5<br/>
5 5 3 5<br/>
5 5 4 5<br/>
5 5 5 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3125<br/>
34<br/>
3 <br/>
2 <br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

