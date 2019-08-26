
# Description

<div class="content"><div id="psrc" style="margin-top: 20px; display: block">
<div class="pdsec"><span style="font-size: medium">　　偶然间，chnlich发现了他小时候玩过的一个游戏“魂斗罗”，于是决定怀旧。但是这是一个奇怪的魂斗罗MOD。<br/>
　　有N个关卡，初始有Q条命。<br/>
　　每通过一个关卡，会得到u分和1条命，生命上限为Q。<br/>
　　其中u=min(最近一次连续通过的关数,R)。<br/>
　　若没有通过这个关卡，将会失去1条命，并进入下一个关卡。<br/>
　　当没有生命或没有未挑战过的关卡时，游戏结束，得到的分数为每关得到的分数的总和。<br/>
　　由于chnlich好久不玩这个游戏了，每条命通过每个关卡的概率均为p(0&lt;=p&lt;=1)，原先chnlich的最高分纪录是S。<br/>
　　现在chnlich想要知道，当p至少为多少时，chnlich期望获得的总分数能够超过原先的最高分。<br/>
</span></div>
</div>
<div id="pcont1" style="margin-top: 20px; display: block"></div></div>

# Input

<div class="content"><div id="pcont1" style="margin-top: 20px; display: block">
<div class="pdcont"><span style="font-size: medium">　　输入共一行，分别表示整数N，整数R，整数Q，原先的最高分整数S。<br/>
</span></div>
</div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　输出共一行，若不存在这样的p，输出&#34;Impossible.&#34;（不包含引号），否则输出p（保留6位小数）。<br/>
</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入一<br/>
　　4 2 1 5<br/>
<br/>
样例输出一<br/>
　　0.880606<br/>
<br/>
样例输入二<br/>
　　12 3 2 12<br/>
<br/>
样例输出二<br/>
　　0.687201<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p>数据规模和约定<br/><br/>
　　对于20%的数据，N&lt;=15<br/><br/>
　　对于50%的数据，N&lt;=10000<br/><br/>
　　对于100%的数据，N&lt;=10^8,1&lt;=R&lt;=20,1&lt;=Q&lt;=5,保证S是一个可能出现的分数。</p><br/>
<p>补充说明<br/><br/>
　　例如，当N=12，R=3，Q=2时<br/><br/>
　　第一关：未通过 u=0 获得分数0 总分为0 剩余生命1<br/><br/>
　　第二关：通过 获得分数1 总分为1 剩余生命2<br/><br/>
　　第三关：通过 获得分数2 总分为3 剩余生命2<br/><br/>
　　第四关：通过 获得分数3 总分为6 剩余生命2<br/><br/>
　　第五关：通过 获得分数3 总分为9 剩余生命2<br/><br/>
　　第六关：未通过 获得分数0 总分为9 剩余生命1<br/><br/>
　　第七关：通过 获得分数1 总分为10 剩余生命2<br/><br/>
　　第八关：未通过 获得分数0 总分为10 剩余生命1<br/><br/>
　　第九关：未通过 获得分数0 总分为10 剩余生命0<br/><br/>
　　游戏结束 总分为10<br/><br/>
　　这是chnlich游戏的一种可能性<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

