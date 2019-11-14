
# Description

<div class="content"><div>
<div>有一棵点数为N的树，树边有边权。给你一个在0~N之内的正整数K，你要在这棵树中选择K个点，将其染成黑色，并</div>
<div>将其他的N-K个点染成白色。将所有点染色后，你会获得黑点两两之间的距离加上白点两两之间距离的和的收益。</div>
<div>问收益最大值是多少。</div>
<div></div>
</div></div>

# Input

<div class="content"><div><span style="font-size: 11.8181819915771px;">第一行两个整数N,K。</span></div>
<div>
<div style="font-size: 11.8181819915771px;">接下来N-1行每行三个正整数fr,to,dis，表示该树中存在一条长度为dis的边(fr,to)。</div>
<div style="font-size: 11.8181819915771px;">输入保证所有点之间是联通的。</div>
<div style="font-size: 11.8181819915771px;">N&lt;=2000,0&lt;=K&lt;=N</div>
<div style="font-size: 11.8181819915771px;"></div>
</div></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">输出一个正整数，表示收益的最大值。</div>
<div style="font-size: 11.8181819915771px;"></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
1 2 3<br/>
1 5 1<br/>
2 3 1<br/>
2 4 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
【样例解释】<br/>
将点1,2染黑就能获得最大收益。</span></div>

# Hint

<div class="content"><p></p><p>2017.9.12新加数据一组 By <span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">GXZlegend</span></p><br/>
<div></div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢bhiaibogf提供">鸣谢bhiaibogf提供</a></p></div>

