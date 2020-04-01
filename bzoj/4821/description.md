
# Description

<div class="content"><div>Frank对天文学非常感兴趣，他经常用望远镜看星星，同时记录下它们的信息，比如亮度、颜色等等，进而估算出</div>
<div>星星的距离，半径等等。Frank不仅喜欢观测，还喜欢分析观测到的数据。他经常分析两个参数之间（比如亮度和</div>
<div>半径）是否存在某种关系。现在Frank要分析参数X与Y之间的关系。他有n组观测数据，第i组观测数据记录了x_i和</div>
<div>y_i。他需要一下几种操作1 L,R：用直线拟合第L组到底R组观测数据。用xx表示这些观测数据中x的平均数，用yy</div>
<div>表示这些观测数据中y的平均数，即</div>
<div>xx=Σx_i/(R-L+1)(L&lt;=i&lt;=R)</div>
<div>yy=Σy_i/(R-L+1)(L&lt;=i&lt;=R)</div>
<div>如果直线方程是y=ax+b，那么a应当这样计算：</div>
<div>a=(Σ(x_i-xx)(y_i-yy))/(Σ(x_i-xx)(x_i-xx)) (L&lt;=i&lt;=R)</div>
<div>你需要帮助Frank计算a。</div>
<div>2 L,R,S,T：</div>
<div>Frank发现测量数据第L组到底R组数据有误差，对每个i满足L &lt;= i &lt;= R，x_i需要加上S，y_i需要加上T。</div>
<div>3 L,R,S,T：</div>
<div>Frank发现第L组到第R组数据需要修改，对于每个i满足L &lt;= i &lt;= R，x_i需要修改为(S+i)，y_i需要修改为(T+i)。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个数n,m，表示观测数据组数和操作次数。</div>
<div>接下来一行n个数，第i个数是x_i。</div>
<div>接下来一行n个数，第i个数是y_i。</div>
<div>接下来m行，表示操作，格式见题目描述。</div>
<div>1&lt;=n,m&lt;=10^5,0&lt;=|S|,|T|,|x_i|,|y_i|&lt;=10^5</div>
<div>保证1操作不会出现分母为0的情况。</div>
<div></div></div>

# Output

<div class="content"><div>对于每个1操作，输出一行，表示直线斜率a。</div>
<div>选手输出与标准输出的绝对误差不超过10^-5即为正确。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
1 2 3<br/>
1 2 3<br/>
1 1 3<br/>
2 2 3 -3 2<br/>
1 1 2<br/>
3 1 2 2 1<br/>
1 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.0000000000<br/>
-1.5000000000<br/>
-0.6153846154</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢infinityedge上传">鸣谢infinityedge上传</a></p></div>

