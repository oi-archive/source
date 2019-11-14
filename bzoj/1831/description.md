
# Description

<div class="content">
小可可和小卡卡想到Y岛上旅游，但是他们不知道Y岛有多远。好在，他们找到一本古老的书，上面是这样说的：
下面是N个正整数，每个都在1~K之间。如果有两个数A和B，A在B左边且A大于B，我们就称这两个数为一个“逆序对”。你数一数下面的数字里有多少个逆序对，你就知道Y岛离这里的距离是多少千米了。
比如说，4 2 1 3 3里面包含了5个逆序对：(4, 2), (4, 1), (4, 3), (4, 3), (2, 1)。
可惜的是，由于年代久远，这些数字里有一部分已经模糊不清了，为了方便记录，小可可用“-1”表示它们。比如说，4 2 -1 -1 3 可能原来是4 2 1 3 3，也可能是4 2 4 4 3，也可能是别的样子。
小可可希望知道，根据他们看清楚的这部分数字，能不能推断出这些数字里最少能有多少个逆序对。

</div>

# Input

<div class="content">第一行两个正整数N和K。第二行N个整数，每个都是-1或是一个在1~K之间的数。
</div>

# Output

<div class="content">一个正整数，即这些数字里最少的逆序对个数。
</div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
4 2 -1 -1 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
</span></div>

# Hint

<div class="content"><p>4 2 4 4 3中有4个逆序对。当然，也存在其它方案得到4个逆序对。<br/>
<br/>
数据范围：<br/>
100%的数据中，N&lt;=10000，K&lt;=100。<br/>
60%的数据中，N&lt;=100。<br/>
40%的数据中，-1出现不超过两次。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

