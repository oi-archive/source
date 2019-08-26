
# Description

<div class="content"><div>由于多次交换邮票没有满足所有人的需求，小Z被赶出了集邮部。无处可去的小Z决定加入音乐部，为了让音乐部的</div>
<div>人注意到自己的才华，小Z想写一首曲子。为了让自己的曲子更好听，小Z找到了一些好听曲子作为模板。曲谱可以</div>
<div>表示成只包含小写字母的字符串，小Z希望自己最终的曲谱中任意一个长度为K的子串都是一个模板的子串。现在小</div>
<div>Z想知道自己的曲谱最长可以是多长，如果可以无限长的话请输出INF。</div>
<p></p></div>

# Input

<div class="content"><div>本题的每个测试点有多组数据，对于每组数据：</div>
<div>第一行两个整数N,K分别表示模板的个数与K值。</div>
<div>接下来N行，每行一个字符串表示一个模板。（只包含&#39;a&#39;~&#39;z&#39;）</div>
<div>每组数据字符串总长不超过100000，1≤K≤100000。每个测试点数据不超过10组。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据输出一行表示曲子最长可以是多长，如果可以无限长的话输出INF。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 4<br/>
abcabc<br/>
1 5<br/>
abcabc</span></div>

# Sample Output

<div class="content"><span class="sampledata">INF<br/>
6<br/>
<br/>
【样例解释】<br/>
第一个样例的曲子可以是&#34;abc&#34;不断循环。<br/>
第二个样例的曲子最长是&#34;abcabc&#34;。<br/>
【Hint】<br/>
对于一个K值来说，任意一个长度小于K的字符串均可行。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

