
# Description

<div class="content"><div>一张n*m的方格纸，有些格子需要印成黑色，剩下的格子需要保留白色。</div>
<div>你有一个a*b的印章，有些格子是凸起（会沾上墨水）的。你需要判断能否用这个印章印出纸上的图案。印的过程中需要满足以下要求：</div>
<div>（1）印章不可以旋转。</div>
<div>（2）不能把墨水印到纸外面。</div>
<div>（3）纸上的同一个格子不可以印多次。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数q(1&lt;=q&lt;=10)，表示测试点数量。</div>
<div>接下来q个测试点，每个测试点中：</div>
<div>第一行包含4个整数n,m,a,b(1&lt;=n,m,a,b&lt;=1000)。</div>
<div>接下来n行，每行m个字符，描述纸上的图案。&#39;.&#39;表示留白，&#39;x&#39;表示需要染黑。</div>
<div>接下来a行，每行b个字符，描述印章。&#39;.&#39;表示不沾墨水，&#39;x&#39;表示沾墨水。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>对于每个测试点，输出TAK（是）或NIE（否）。</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 4 4 2<br/>
xx..<br/>
.xx.<br/>
xx..<br/>
x.<br/>
.x<br/>
x.<br/>
..<br/>
2 2 2 2<br/>
xx<br/>
xx<br/>
.x<br/>
x.</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
NIE</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

