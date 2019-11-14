<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们使用黑匣子的一个简单模型。它能存放一个整数序列和一个特别的变量i。在初始时刻，黑匣子为空且i等于0。这个黑匣子能执行一系列的命令。有两类命令：</p>
<p>ADD(x)：把元素x放入黑匣子；GET：把i加1的同时，输出黑匣子内所有整数中第i小的数。牢记第i小的数是当黑匣子中的元素已非降序排序后位于第i位的元素。</p>
<p>下面的表6_4是一个11个命令的例子：</p>
<p>表6_4</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td width="76">
<p>编号</p>
</td>
<td width="132">
<p>命令</p>
</td>
<td width="66">
<p>i</p>
</td>
<td width="155">
<p>黑匣子内容</p>
</td>
<td width="78">
<p>输出</p>
</td>
</tr>
<tr>
<td width="76">
<p>1</p>
</td>
<td width="132">
<p>ADD(3)</p>
</td>
<td width="66">
<p>0</p>
</td>
<td width="155">
<p>3</p>
</td>
<td width="78">
<p> </p>
</td>
</tr>
<tr>
<td width="76">
<p>2</p>
</td>
<td width="132">
<p>GET</p>
</td>
<td width="66">
<p>1</p>
</td>
<td width="155">
<p>3</p>
</td>
<td width="78">
<p>3</p>
</td>
</tr>
<tr>
<td width="76">
<p>3</p>
</td>
<td width="132">
<p>ADD(1)</p>
</td>
<td width="66">
<p>1</p>
</td>
<td width="155">
<p>1,3</p>
</td>
<td width="78">
<p> </p>
</td>
</tr>
<tr>
<td width="76">
<p>4</p>
</td>
<td width="132">
<p>GET</p>
</td>
<td width="66">
<p>2</p>
</td>
<td width="155">
<p>1,3</p>
</td>
<td width="78">
<p>3</p>
</td>
</tr>
<tr>
<td width="76">
<p>5</p>
</td>
<td width="132">
<p>ADD(-4)</p>
</td>
<td width="66">
<p>2</p>
</td>
<td width="155">
<p>-4,1,3</p>
</td>
<td width="78">
<p> </p>
</td>
</tr>
<tr>
<td width="76">
<p>6</p>
</td>
<td width="132">
<p>ADD(2)</p>
</td>
<td width="66">
<p>2</p>
</td>
<td width="155">
<p>-4,1,2,3</p>
</td>
<td width="78">
<p> </p>
</td>
</tr>
<tr>
<td width="76">
<p>7</p>
</td>
<td width="132">
<p>ADD(8)</p>
</td>
<td width="66">
<p>2</p>
</td>
<td width="155">
<p>-4,1,2,3,8</p>
</td>
<td width="78">
<p> </p>
</td>
</tr>
<tr>
<td width="76">
<p>8</p>
</td>
<td width="132">
<p>ADD(-1000)</p>
</td>
<td width="66">
<p>2</p>
</td>
<td width="155">
<p>-1000,-4,1,2,3,8</p>
</td>
<td width="78">
<p> </p>
</td>
</tr>
<tr>
<td width="76">
<p>9</p>
</td>
<td width="132">
<p>GET</p>
</td>
<td width="66">
<p>3</p>
</td>
<td width="155">
<p>-1000,-4,1,2,3,8</p>
</td>
<td width="78">
<p>1</p>
</td>
</tr>
<tr>
<td width="76">
<p>10</p>
</td>
<td width="132">
<p>GET</p>
</td>
<td width="66">
<p>4</p>
</td>
<td width="155">
<p>-1000,-4,1,2,3,8</p>
</td>
<td width="78">
<p>2</p>
</td>
</tr>
<tr>
<td width="76">
<p>11</p>
</td>
<td width="132">
<p>ADD(2)</p>
</td>
<td width="66">
<p>4</p>
</td>
<td width="155">
<p>-1000,-4,1,2,2,3,8</p>
</td>
<td width="78">
<p> </p>
</td>
</tr>
</tbody>
</table>
<p>现需要一个有效的算法处理给定的一系列命令。ADD和GET命令的总数至多个有30000个。定义ADD命令的个数为M个，GET命令的个数为N个。我们用下面得两个整数序列描述命令序列：</p>
<p>1．A(1),A(2),……,A(M)：加入黑匣子的元素序列。所有的数均为绝对值不超过2000000的整数。例如在上例中A=(3,1,-4,2,8,-1000,2)。</p>
<p>2．u(1),u(2),……,u(N)：u(i)表示第i个GET命令在第u(i)个ADD命令之后，例如在上例中，u=(1,2,6,6)。</p>
<p>你可以假定自然数序列u(1),u(2),……,u(N)以非降序排列，N≤M，且对于每一个p（1≤p≤N）有p≤u(p)≤M。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行存放M和N的值,第二行存放 A(1),A(2),……,A(M) ,第三行存放u(1),u(2),……,u(N)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出黑匣子的处理结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 4</p>
<p>3 1 -4 2 8 -1000 2</p>
<p>1 2 6 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>3</p>
<p>1</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>