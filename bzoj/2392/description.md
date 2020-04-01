
# Description

<div class="content"><p>    从前在一个森林中，有好多好多只变色龙，每只变色龙有自己的初始颜色Ci，变色龙们没事的时候，喜欢玩一个游戏，<br/>
    所有变色龙站在一个长度为L的圆环上，每只变色龙的初始位置位置pi，他们有的按照顺时针方向走，有的按照逆时针方向走.<br/>
    当方向不同的两只变色龙相遇的时候，逆时针的变色龙的颜色变成和顺时针的变色龙颜色一样，顺时针的变色龙颜色不变，并且两只变色龙掉头向反方向继续走。</p>
<p>    请你计算一下，T时间后，每只变色龙的颜色和位置以及他们的方向。</p>
<p></p></div>

# Input

<div class="content"><p><br/>
第一行是一个数n，表示有n只变色龙，第二行是一个数L，表示圆环的长度<br/>
接下来有n行，每行三个数pi,ci,di<br/>
pi表示每只变色龙位置，<br/>
Ci表示每只变色龙的颜色<br/>
Di表示每只变色龙的方向，+1表示顺时针，-1表示逆时针</p>
<p></p></div>

# Output

<div class="content"><p>N行数，每行三个数，分别表示T时间后每只变色龙的pi ，ci ，di<br/>
Pi保留三位小数</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
13<br/>
2 1 1<br/>
0 2 -1<br/>
12 3 1<br/>
5 2 1<br/>
23<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2.000 2 1<br/>
12.000 1 1<br/>
9.000 3 1<br/>
3.000 3 -1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于40%数据   n&lt;=100<br/><br/>
对于60%数据   n&lt;=1000<br/><br/>
对于100%数据     （n&lt;=10^5，L&lt;=10^9，0&lt;=pi&lt;L，1&lt;=ci&lt;=10^9，T&lt;=10^18<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

