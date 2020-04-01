
# Description

<div class="content"><p><img height="358" alt="" width="761" src="/source/bzoj/3230/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNi9hYS5qcGc=.jpg"/></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入第1行，包含3个整数N，Q。Q代表询问组数。<br/>
第2行是字符串S。<br/>
接下来Q行，每行两个整数i和j。（1≤i≤j）。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出共Q行，每行一个数表示每组询问的答案。如果不存在第i个子串或第j个子串，则输出-1。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
ababa<br/>
3 5<br/>
5 9<br/>
8 10<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">18<br/>
16<br/>
-1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>样例解释<br/><br/>
第1组询问：两个子串是“aba”,“ababa”。f = 32 + 32 = 18。<br/><br/>
第2组询问：两个子串是“ababa”,“baba”。f = 02 + 42 = 16。<br/><br/>
第3组询问：不存在第10个子串。输出-1。</p><br/>
<p>数据范围<br/><br/>
N≤100000，Q≤100000，字符串只由小写字母&#39;a&#39;~&#39;z&#39;组成</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

