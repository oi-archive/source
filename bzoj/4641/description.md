
# Description

<div class="content"><div>&#34;人类智慧的冰峰，只有萌萌哒的我寂寞地守望。&#34;</div>
<div>--TB</div>
<div></div>
<div>TB正走在改造人类智慧基因的路上。TB发现人类智慧基因一点也不萌萌哒，导致人类普遍智商过低，为了拯救低智</div>
<div>商人群，博爱的TB开始改造人类智慧基因。人类智慧DNA由C种人类智慧脱氧核苷酸构成（这是一种十分特殊的DNA</div>
<div>）。TB智慧DNA片段T长度为M，她可以把另一段长度为M的人类智慧DNA片段S改造成T。改造过程中，TB可以充分发</div>
<div>挥智慧，将任意两种人类智慧脱氧核苷酸交换（比如对于片段S=12321，交换1和2变成S=21312，交换1和4变成4232</div>
<div>4），可以无限次交换。如果S可以通过若干次交换变成T，那么就称S为&#34;萌萌哒人类基因片段&#34;。TB想知道对于一个</div>
<div>长度为N的人类智慧DNA片段S[1~N]，有多少个长度为M的连续子片段S[i~i+M-1]，是&#34;萌萌哒人类基因片段&#34;，并且</div>
<div>这些&#34;萌萌哒人类基因片段&#34;在哪里。</div></div>

# Input

<div class="content"><div>输入文件的第一行包含两个正整数case和C，分别表示数据组数和人类智慧脱氧核苷酸的种数。</div>
<div>接下来3*case行，每三行表示一组数据：</div>
<div>第一行一个正整数N和M，表示人类智慧DNA片段S和TB智慧DNA片段T的长度。</div>
<div>第二行N个正整数，表示人类智慧DNA片段S。</div>
<div>第三行M个正整数，表示TB智慧DNA片段T。</div>
<div>对于所有数据数据，case=3, n,m,C&lt;=1000000</div></div>

# Output

<div class="content"><div>对于每组数据：</div>
<div>第一行一个正整数tot，表示&#34;萌萌哒人类基因片段&#34;的个数。</div>
<div>接下来一行tot个用空格隔开的正整数pos，表示&#34;萌萌哒人类基因片段&#34;开头所在的位置。要求从小到大输出每个pos。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
6 3<br/>
1 2 1 2 3 2<br/>
3 1 3<br/>
6 3<br/>
1 2 1 2 1 2<br/>
3 1 3<br/>
6 3<br/>
1 1 2 1 2 1<br/>
3 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1 2 4<br/>
4<br/>
1 2 3 4<br/>
3<br/>
2 3 4<br/>
对于第一组数据：<br/>
S[1~3]=121，可以先将1和2交换变成212，再将2和3交换变成313。<br/>
S[2~4]=212，可以将2和3交换变成313。<br/>
S[4~6]=232，可以先将2和3交换变成323，再将1和2交换变成313。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

