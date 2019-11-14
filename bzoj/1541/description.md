
# Description

<div class="content"><p><span style="font-size: medium">镜子迷宫是一个用镜子做成的立方体. 在立方体的几何中心有一个激光发射器(它发射的激光大小可以忽略). 你的任务是发射一条激光射线使得这条射线走过尽量长的路程后回到发射点. 路程我们使用曼哈顿距离衡量. 迷宫的长度都是偶数. 迷宫上的顶点和棱都不反射激光. 在立方体内部我们使用笛卡儿坐标系来描述顶点,激光发射器位于原点即(0, 0, 0). </span></p></div>

# Input

<div class="content"><div>一个测试文件中有很多镜子迷宫需要计算. </div>
<div>第一行一个整数1 &lt;= K &lt;= 1000, 表示迷宫总数. </div>
<div>第 2 ... K + 1 行每行三个数, 表示迷宫的长宽高的1/2,该迷宫的形状是一个2x2y2z的立方体.</div>
<div>5 &lt;= x, y, z &lt;= 1000</div></div>

# Output

<div class="content"><div>你的程序应该输出K 行. </div>
<div>第 i行包含第i个迷宫的解答: </div>
<div>三个整数kx, ky, kz, , 表示对于第i个迷宫其激光发射器该朝点(kx, ky, kz)发射激光.</div>
<div>如果有多解输出任意一组.</div>
<div>- x &lt;= kx &lt;= x, - y &lt;= ky &lt;= y, - z &lt;= kz &lt;= z, (kx, ky, kz) &lt;&gt; (0, 0, 0)</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
5 6 7<br/>
5 6 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 5 6<br/>
4 6 5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

