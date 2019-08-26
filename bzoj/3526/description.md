
# Description

<div class="content"><p><span style="font-size: medium">有n张卡片在桌上一字排开，每张卡片上有两个数，第i张卡片上，正面的数为a[i]，反面的数为b[i]。现在，有m个熊孩子来破坏你的卡片了！<br/>
第i个熊孩子会交换c[i]和d[i]两个位置上的卡片。<br/>
每个熊孩子捣乱后，你都需要判断，通过任意翻转卡片（把正面变为反面或把反面变成正面，但不能改变卡片的位置），能否让卡片正面上的数从左到右单调不降。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个n。<br/>
接下来n行，每行两个数a[i],b[i]。<br/>
接下来一行一个m。<br/>
接下来m行，每行两个数c[i],d[i]。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">m行，每行对应一个答案。如果能成功，输出TAK，否则输出NIE。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 5<br/>
3 4<br/>
6 3<br/>
2 7<br/>
2<br/>
3 4<br/>
1 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">NIE<br/>
TAK<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
【样例解释】<br/><br/>
交换3和4后，卡片序列为(2,5) (3,4) (2,7) (6,3)，不能成功。<br/><br/>
交换1和3后，卡片序列为(2,7) (3,4) (2,5) (6,3)，翻转第3张卡片，卡片的正面为2,3,5,6，可以成功。</span></p><br/>
<p><span style="font-size: medium">【数据范围】<br/><br/>
n≤200000，m≤1000000，0≤a[i],b[i]≤10000000,1≤c[i],d[i]≤n.</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Dzy">By Dzy</a></p></div>

