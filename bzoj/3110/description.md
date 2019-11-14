
# Description

<div class="content"><p><span style="font-size: medium">有N个位置，M个操作。操作有两种，每次操作如果是1 a b c的形式表示在第a个位置到第b个位置，每个位置加入一个数c<br/>
如果是2 a b c形式，表示询问从第a个位置到第b个位置，第C大的数是多少。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行N，M<br/>
接下来M行，每行形如1 a b c或2 a b c</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出每个询问的结果</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 5<br/>
1 1 2 1<br/>
1 1 2 2<br/>
2 1 1 2<br/>
2 1 1 1<br/>
2 1 2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
1</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
【样例说明】<br/><br/>
第一个操作 后位置 1 的数只有 1 ， 位置 2 的数也只有 1 。 第二个操作 后位置 1<br/><br/>
的数有 1 、 2 ，位置 2 的数也有 1 、 2 。 第三次询问 位置 1 到位置 1 第 2 大的数 是<br/><br/>
1 。 第四次询问 位置 1 到位置 1 第 1 大的数是 2 。 第五次询问 位置 1 到位置 2 第 3<br/><br/>
大的数是 1 。‍</p><br/>
<p>N,M&lt;=50000,N,M&lt;=50000<br/><br/>
a&lt;=b&lt;=N<br/><br/>
1操作中abs(c)&lt;=N<br/><br/>
2操作中c&lt;=Maxlongint</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

