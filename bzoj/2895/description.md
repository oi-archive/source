
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">在一个篮球联赛里，有n支球队，球队的支出是和他们的胜负场次有关系的，具体来说，第i支球队的赛季总支出是Ci*x^2+Di*y^2，Di&lt;=Ci。(赢得多，给球员的奖金就多嘛)</span></div>
<div><span style="font-size: medium">其中x,y分别表示这只球队本赛季的胜负场次。现在赛季进行到了一半，每只球队分别取得了a[i]场胜利和b[i]场失利。而接下来还有m场比赛要进行。问联盟球队的最小总支出是多少。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行n，m</span></div>
<div><span style="font-size: medium">接下来n行每行4个整数a[i],b[i],Ci,Di</span></div>
<div><span style="font-size: medium">再接下来m行每行两个整数s，t表示第s支队伍和第t支队伍之间将有一场比赛，注意两只队间可能有多场比赛。</span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">输出总支出的最小值。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 3<br/>
1 0 2 1<br/>
1 1 10 1<br/>
0 1 3 3<br/>
1 2<br/>
2 3<br/>
3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
43<br/>
Data Limit<br/>
对于20%的数据2&lt;=n&lt;=10,0&lt;=m&lt;=20<br/>
对于100%的数据2&lt;=n&lt;=5000,0&lt;=m&lt;=1000,0&lt;=di&lt;=ci&lt;=10,0&lt;=a[i],b[i]&lt;=50.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

