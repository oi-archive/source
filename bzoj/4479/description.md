
# Description

<div class="content"><p>【故事背景】<br/>
作为JSOI的著名吃货，JYY的理想之一就是吃遍全世界的美食。要走遍全<br/>
世界当然需要不断的坐飞机了。而不同的航班上所提供的餐食是很不一样的：比<br/>
如中国的航班会提供中餐，英国的航班有奶茶和蛋糕，澳大利亚的航班有海鲜，<br/>
新加坡的航班会有冰激凌……JYY选出了一些他特别希望品尝餐食的航班，希望<br/>
制定一个花费最少的旅游计划，能够从南京出发，乘坐所有这些航班并最后回到<br/>
南京。<br/>
【问题描述】<br/>
世界上一共有N个JYY愿意去的城市，分别从1编号到N。JYY选出了K<br/>
个他一定要乘坐的航班。除此之外，还有M个JYY没有特别的偏好，可以乘坐<br/>
也可以不乘坐的航班。<br/>
一个航班我们用一个三元组(x,y,z)来表示，意义是这趟航班连接城市x和y，<br/>
并且机票费用是z。每个航班都是往返的，所以JYY花费z的钱，既可以选择从<br/>
x飞往y，也可以选择从y飞往x。<br/>
南京的编号是1，现在JYY打算从南京出发，乘坐所有K个航班，并且最<br/>
后回到南京，请你帮他求出最小的花费。<br/>
<br/>
<br/>
</p></div>

# Input

<div class="content"><p>输入数据的第一行包含两个整数N和K；<br/>
接下来K行，每行三个整数x，y，z描述必须乘坐的航班的信息，数据保证<br/>
在这K个航班中，不会有两个不同的航班在同一对城市之间执飞；<br/>
第K+2行包含一个整数M；<br/>
接下来M行，每行三个整数x，y，z描述可以乘坐也可以不乘坐的航班信息。<br/>
2&lt;=N&lt;=13，0&lt;=K&lt;=78，2&lt;=M&lt;=200，1&lt;=x,y&lt;=N，1&lt;=z&lt;=10^4</p></div>

# Output

<div class="content"><p>输出一行一个整数，表示最少的花费。数据保证一定存在满足JYY要求的<br/>
旅行方案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
1 2 1000<br/>
2 3 1000<br/>
4 5 500<br/>
2<br/>
1 4 300<br/>
3 5 300</span></div>

# Sample Output

<div class="content"><span class="sampledata">3100<br/>
一个可行的最佳方案为1-&gt;2-&gt;3-&gt;5-&gt;4-&gt;1。<br/>
机票所需的费用为1000+1000+300+500+300=3100</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

