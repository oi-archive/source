
# Description

<div class="content"><p><img src="/source/bzoj/4267/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwOS8xMSgyKS5wbmc=.png" width="675" height="903" alt=""/></p>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数P，M，表示书的颜色数、小强的行为数。接下来描述</div>
<div>了一个心情系统。第一行是心情数N，接下来N行每行P个正整数表示数组A，接下来一</div>
<div>行N个正整数表示数组B。P&gt;=1，M&gt;=1，N&gt;=1。注意：某些心情或者某些行为可能</div>
<div>是小强永远也不会达到或者做出的。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>描述了和输入等效的心情数最少的心情系统。第一行一个正整数，表示</div>
<div>心情数，接下来按照输入文件的格式描述这个心情系统的数组A和数组B。如果有多种可能</div>
<div>的心情系统的心情数都是最小的，你要输出字典序最小的，即，A[1][1]最小，在此前提下，</div>
<div>A[1][2] …… 最小 在A数组相同的情况下，B[1]最小，在此前提下，B[2] …… 最小。注意，</div>
<div>你要满足 &#34;空白&#34;（即小强开始看书的心情）的心情编号是1。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
6<br/>
2 3<br/>
4 6<br/>
4 5<br/>
6 5<br/>
5 2<br/>
6 3<br/>
1 1 1 1 2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 <br/>
2 2 <br/>
3 4 <br/>
4 4 <br/>
4 2 <br/>
1 1 1 2</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，N&lt;=1000，P&lt;=26，M&lt;=1000</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

