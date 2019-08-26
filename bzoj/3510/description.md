
# Description

<div class="content"><p style="text-align: left"><span style="font-size: medium"><font face="Times New Roman">在X星球上有N个国家，每个国家占据着X星球的一座城市。由于国家之间是敌对关系，所以不同国家的两个城市是不会有公路相连的。 <br/>
X星球上战乱频发，如果A国打败了B国，那么B国将永远从这个星球消失，而B国的国土也将归A国管辖。A国国王为了加强统治，会在A国和B国之间修建一条公路，即选择原A国的某个城市和B国某个城市，修建一条连接这两座城市的公路。 <br/>
同样为了便于统治自己的国家，国家的首都会选在某个使得其他城市到它距离之和最小的城市，这里的距离是指需要经过公路的条数，如果有多个这样的城市，编号最小的将成为首都。 <br/>
现在告诉你发生在X星球的战事，需要你处理一些关于国家首都的信息，具体地，有如下3种信息需要处理： <br/>
1、A x y：表示某两个国家发生战乱，战胜国选择了x城市和y城市，在它们之间修建公路（保证其中城市一个在战胜国另一个在战败国）。 <br/>
2、Q x：询问当前编号为x的城市所在国家的首都。 <br/>
3、Xor：询问当前所有国家首都编号的异或和。 <br/>
</font></span></p></div>

# Input

<div class="content"><p><font face="Times New Roman" size="4">第一行是整数N，M，表示城市数和需要处理的信息数。 <br/>
接下来每行是一个信息，格式如题目描述（A、Q、Xor中的某一种）。 <br/>
</font></p></div>

# Output

<div class="content"><p><font face="Times New Roman" size="4">输出包含若干行，为处理Q和Xor信息的结果。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 10 <br/>
Xor <br/>
Q 1 <br/>
A 10 1 <br/>
A 1 4 <br/>
Q 4 <br/>
Q 10 <br/>
A 7 6 <br/>
Xor <br/>
Q 7 <br/>
Xor <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11 <br/>
1 <br/>
1 <br/>
1 <br/>
2 <br/>
6 <br/>
2 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于100%的数据，2&lt;=N&lt;=100000，1&lt;=M&lt;=200000。 <br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

