
# Description

<div class="content"><img border="0" src="/source/bzoj/1553/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE1NTNfMS5qcGc=.jpg"/>
<img border="0" src="/source/bzoj/1553/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE1NTNfMi5qcGc=.jpg"/>  
计算给定范围内有多少种输入可以使输出为1。
我们假设3 &lt; n &lt; 100, 3 &lt; m &lt; 3000，而且网络中的门是用1到m之间的数任意编号的。

</div>

# Input

<div class="content">文件第一行包含三个整数，分别表示输入的个数，门的个数，连接到输出的门的编号。以下的m行描述网络中的连接情况。第I行表示第I个门的两个输入，两个输入为范围[-n,m]之间的一个整数。如果输入是网络的第k个输入，则连接的描述是一个整数－k，如果输入是第j个门，则连接的描述是一个整数j。以下两行各有一个n位二进制串，表示输入的上限和下限。

</div>

# Output

<div class="content">包含一个整数，表示给定范围内有多少种输入可以使输出为1。

</div>

# Sample Input

<div class="content"><span class="sampledata">5 6 5<br/>
-1 -2<br/>
1 3<br/>
1 -2<br/>
2 -3<br/>
4 6<br/>
-4 -5<br/>
00111<br/>
01110<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=HNOI2009集训Day7">HNOI2009集训Day7</a></p></div>

