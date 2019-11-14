
# Description

<div class="content"><div><span style="font-size: medium">  编号为1到N的N只奶牛正各自驾着车打算在牛德比亚的高速公路上飞驰．高速公路有M(1≤M≤N)条车道．奶牛i有一个自己的车速上限Si(l≤Si≤1,000,000)．</span></div>
<div><span style="font-size: medium">    在经历过糟糕的驾驶事故之后，奶牛们变得十分小心，避免碰撞的发生．每条车道上，如果某一只奶牛i的前面有K只奶牛驾车行驶，那奶牛i的速度上限就会下降K*D个单位，也就是说，她的速度不会超过Si - kD(O≤D≤5000)，当然如果这个数是负的，那她的速度将是0．牛德比亚的高速会路法规定，在高速公路上行驶的车辆时速不得低于/(1≤L≤1,000,000)．那么，请你计算有多少奶牛可以在高速公路上行驶呢？</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第1行输入N，M，D，L四个整数，之后N行每行一个整数输入Si．</span></div>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">N&lt;=50000</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    输出最多有多少奶牛可以在高速公路上行驶．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 1 1 5//三头牛开车过一个通道.当一个牛进入通道时，它的速度V会变成V-D*X(X代表在它前面有多少牛),它减速后，速度不能小于L<br/>
5<br/>
7<br/>
5<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are three cows with one lane to drive on, a speed decrease<br/>
of 1, and a minimum speed limit of 5.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Two cows are possible, by putting either cow with speed 5 first and the cow<br/>
with speed 7 second.<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

