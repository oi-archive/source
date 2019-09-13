# 题目描述


<div style="line-height:15pt;" align="left">
<b>【问题描述】</b><br/>
我们使用黑匣子的一个简单模型。它能存放一个整数序列和一个特别的变量i。在初始时刻，黑匣子为空且i等于0。这个黑匣子能执行一系列的命令。有两类命令： ADD(x)：把元素x放入黑匣子；GET：把i加1的同时，输出黑匣子内所有整数中第i小的数。牢记第i小的数是当黑匣子中的元素已非降序排序后位于第i位的元素。<br/>
下面的表是一个11个命令的例子：
</div>
<div style="line-height:15pt;" align="left">
 
</div>
<table border="1" cellspacing="1" cellpadding="1" width="571" align="center" height="263">
<tbody>
<tr>
<td>
编号
</td>
<td>
命令
</td>
<td>
i
</td>
<td>
黑匣子内容
</td>
<td>
输出
</td>
</tr>
<tr>
<td>
1
</td>
<td>
ADD(3)
</td>
<td>
0
</td>
<td>
3
</td>
<td>
 
</td>
</tr>
<tr>
<td>
2
</td>
<td>
GET
</td>
<td>
1
</td>
<td>
3
</td>
<td>
3
</td>
</tr>
<tr>
<td>
3
</td>
<td>
ADD(1)
</td>
<td>
1
</td>
<td>
1,3
</td>
<td>
 
</td>
</tr>
<tr>
<td>
4
</td>
<td>
GET
</td>
<td>
2
</td>
<td>
1,3
</td>
<td>
3
</td>
</tr>
<tr>
<td>
5
</td>
<td>
ADD(-4)
</td>
<td>
2
</td>
<td>
-4,1,3
</td>
<td>
 
</td>
</tr>
<tr>
<td>
6
</td>
<td>
ADD(2)
</td>
<td>
2
</td>
<td>
-4,1,2,3
</td>
<td>
 
</td>
</tr>
<tr>
<td>
7
</td>
<td>
ADD(8)
</td>
<td>
2
</td>
<td>
-4,1,2,3,8
</td>
<td>
 
</td>
</tr>
<tr>
<td>
8
</td>
<td>
ADD(-1000)
</td>
<td>
2
</td>
<td>
-1000,-4,1,2,3,8
</td>
<td>
 
</td>
</tr>
<tr>
<td>
9
</td>
<td>
GET
</td>
<td>
3
</td>
<td>
-1000,-4,1,2,3,8
</td>
<td>
1
</td>
</tr>
<tr>
<td>
10
</td>
<td>
GET
</td>
<td>
4
</td>
<td>
-1000,-4,1,2,3,8
</td>
<td>
2
</td>
</tr>
<tr>
<td>
11
</td>
<td>
ADD(2)
</td>
<td>
4
</td>
<td>
-1000,-4,1,2,2,3,8
</td>
<td>
 
</td>
</tr>
</tbody>
</table>
<div style="line-height:15pt;" align="left">
 
</div>
<div style="line-height:15pt;" align="left">
现需要一个有效的算法处理给定的一系列命令。ADD和GET命令的总数至多有30000个。定义ADD命令的个数为M个，GET命令的个数为N个。我们用下面的两个整数序列描述命令序列：<br/>
(1)A(1)，A(2)，…，A(M)：加入黑匣子的元素序列。所有的数均为绝对值不超过2000000的整数。例如在上例中A＝(3，1，-4，2，8，-1000，2)。<br/>
(2)u(1)，u(2)，…，u(N)：u(i)表示第i个GET命令在第u(i)个ADD命令之后，例如在上例中，u＝(1，2，6，6)。<br/>
你可以假定自然数序列u(1)，u(2)，…，u(N)以非降序排列，N≤M，且对于每一个p(1≤p≤N)有p≤u(p)≤M。<br/>
<br/>
【输入格式】 <br/>
     输入文件名为blackbox.in，其中第一行存放M和N的值，第二行存放A(1)，A(2)，…，<br/>
A(M)，第三行存放u(1)，u(2)，…，u(N)。
</div>
<div style="line-height:15pt;" align="left">
【输出格式】 <br/>
   输出黑匣子的处理结果。<br/>
【输入输出样例】 <b><br/>
</b>输入:<br/>
blackbox.in<br/>
7 4<br/>
3 1 -4 2 8 -1000 2<br/>
1 2 6 6
</div>
<div style="line-height:15pt;" align="left">
输出:<br/>
blackbox.out<br/>
3 <br/>
3 <br/>
1 <br/>
2
</div>
