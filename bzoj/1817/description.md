
# Description

<div class="content">Hilbert鼹鼠住在Hilbert地洞里——地洞的边界是一条n阶Hilbert曲线Hn。Hilbert曲线的定义如下：H1是一个上端缺口的单位正方形；Hn由四份Hn-1组成，其中左下和右下两份没有任何变化，而左上的那一份逆时针旋转了90度，而右上的那一份顺时针旋转了90度。这四份Hn-1用三条单位长度的线段连接起来构成了Hn。H1~H4如下图所示：
<img border="0" src="/source/bzoj/1817/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4MTdfMS5qcGc=.jpg"/> 

你想捉一只Hilbert鼹鼠来玩，所以往地洞里使劲倒水想把它们赶出来。不过，由于地洞里有空气，无论你怎么倒水，有些地方总是淹不到的（假设水和空气都不可压缩）。输入Hilbert曲线的阶数n和地面的倾斜角α，你的任务是计算能淹没到的面积。
<img border="0" src="/source/bzoj/1817/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4MTdfMi5qcGc=.jpg"/>
注意，只有当水位严格高于一个障碍物时，水才能越过它往下流。更多细节可以参考下面的例子。
<img border="0" src="/source/bzoj/1817/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4MTdfMy5qcGc=.jpg"/>
</div>

# Input

<div class="content">输入仅包含两个整数n，α。

</div>

# Output

<div class="content">输出仅一行，即被淹没的面积，输出保留小数点后6位。

</div>

# Sample Input

<div class="content"><span class="sampledata">mole.in	mole.out<br/>
5 30	190.803848<br/>
mole.in	mole.out<br/>
3 45	15.500000<br/>
mole.in	mole.out<br/>
4 10	91.573592<br/>
mole.in	mole.out<br/>
3 0	26.000000<br/>
<br/>
数据范围<br/>
编号	1	2	3	4	5	6	7	8	9	10<br/>
n	1	2	3	4	4	6	8	10	12	12<br/>
α	[0,90)	[0,90)	[0,90)	0	45	[0,90)	[0,90)	[0,90)	0	[0,90)<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

