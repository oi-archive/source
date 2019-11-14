
# Description

<div class="content">做了AHOI2006的Board一题，YY觉得天昏地暗，回肠荡气，余音绕梁……
YY也就想出了一个问题：对于一个完全二分图，有多少种不同的完备匹配？
结果YY发现这个问题太简单了，根本难不倒大家。
YY就改进了一下，对于一个有2N个节点的完全二分图，包含边数为0，为1，为2……为N的匹配分别有多少？
YY经过研究，发现此题存在N种解法，甚至可以交表！
绝望的YY心想，这下子伤自尊了，题目没法出了。好在他这时突然又想起了Board那题。“对啊！”YY说，“我在图中删去M条边，再问你们包含边数为0，为1，为2……为N的匹配分别有多少，这样就没办法交表了。”
于是，问题就出来了。可惜的是，这下子YY真的不会做了……大家会做的话帮一下YY吧。

</div>

# Input

<div class="content">第一行两个整数N和M，定义见上文。1&lt;=N&lt;=500，0&lt;=M&lt;=20。
后面M行，每行有两个数A和B，表示YY删去的一条边——二分图左边部分编号为A的节点与二分图右边部分编号为B的节点。二分图的两个部分的节点都分别编号为1..N。

</div>

# Output

<div class="content">N+1行，分别表示包含边数为0，为1，为2……为N的匹配分别有多少。

</div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
1 2<br/>
1 3<br/>
2 1<br/>
2 3<br/>
3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
4<br/>
4<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p><img border="0" src="/source/bzoj/1439/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0MzkuanBn.jpg"/><br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

