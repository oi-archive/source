# 题目描述


<p>
这场灾难发生后，国家决定设立研究所研究灾后重建工作，由全国各地派技术人员来参加。因为每个地区所派的技术人员数目不同，由于节约经费的问题，所以目前还没有决定到底要灾哪个地区设置研究所进行研究。假设所有地区都在一条直线上，现在只知道每个地区与汶川的距离和该地派出技术人员的数目（假设汶川在最左端）。请你编程帮助他们确定在哪个地区建立研究所可以使所有技术人员集中到该地区的费用总和最小。
</p>
<p>
[ 输入文件 ]
</p>
<p>
输入文件的每一行描述一个地区的信息（地区数≤ 5000 ）
</p>
<p>
对于每一行，首先是该地区派出的技术人员数目，紧跟着的是这个地区相对于汶川的距离，最后是该地区的名称。（ 0 ＜技术人员数≤ 100 ， 0 ≤地区相对距离≤ 10^31 ，地区名称长度≤ 20, 数据保证于唯一解。）
</p>
<p>
[ 输出文件 ]
</p>
<p>
输入文件只需要一行，即研究所设定的地区名称。
</p>
<p>
[ 输入样例 ]
</p>
<p>
7 9289 shengyan <br/>
5 8523 beijing <br/>
3 5184 guilin <br/>
8 2213 chongqing <br/>
10 0 wuhan
</p>
<p>
 
</p>
<p>
[ 输出样例 ]
</p>
<p>
chongqing
</p>