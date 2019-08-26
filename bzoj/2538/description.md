
# Description

<div class="content"><div><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"><span style="color: black">在一条没有分岔的高速公路上有n个关口，相邻两个关口之间的距离都是10km。所有车辆在这条高速公路上的最低速度为60km/h，最高速度为120km/h，并且只能在关口处改变速度。</span></span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"><span style="color: black">巡逻的方式是在某个时刻T<sub>i</sub>从第n<sub>i</sub>个关口派出一辆巡逻车匀速驶抵第(n<sub>i</sub>+1)个关口，路上耗费的时间为t<sub>i</sub>秒。</span></span></div>
<div><span style="font-size: medium">两辆车相遇是指它们之间发生超车或者两车同时到达某关口（同时出发不算相遇）。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"><span style="color: black">巡逻部门想知道一辆于6点整从第1个关口出发去第n个关口的车（称为目标车）最少会与多少辆巡逻车相遇，请编程计算之。假设所有车辆到达关口的时刻都是整秒。</span></span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 24pt"><span style="font-size: medium"><span style="color: black">输入文件第一行为两个用空格隔开的整数，分别为关口数n和巡逻车数m。（1&lt;n&lt;50,1&lt;m&lt;300），接下来的m行每一行为一辆巡逻车的信息（按出发位置递增排序），格式为n<sub>i</sub>　T<sub>i</sub>　t<sub>i</sub>，三项用空格隔开，分别表示第i辆巡逻车的出发位置、出发时刻和路上耗费的时间，其中n<sub>i</sub>和t<sub>i</sub>为整数，T<sub>i</sub>形如hhmmss，表示时、分、秒，采用24小时制，不足两位的数用前置0补齐。（1&lt;=n<sub>i</sub>&lt;n,05:00:00&lt;=T<sub>i</sub>&lt;=23:00:00,300&lt;=t<sub>i</sub>&lt;=600）</span></span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="text-indent: 24pt"><span style="font-size: medium"><span style="color: black">输出文件第一行为目标车与巡逻车相遇次数。第二行为目标车与巡逻车相遇次数最少时最早到达第n个关口的时刻（格式同输入中的T<sub>i</sub>）。</span></span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
1 060000 301<br/>
2 060300 600<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
061301</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

