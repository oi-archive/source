<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>冰冰有三个玩具：皮卡秋、维妮孙悟空和芭比娃娃。她并不知道这些玩具的具体重量（采用NOI单位），但是知道每个玩具重量的大概范围，如下表：</p>
<table border="0" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="142">
<p><strong> </strong></p>
</td>
<td valign="top" width="142">
<p><strong>皮卡秋</strong><strong></strong></p>
</td>
<td valign="top" width="142">
<p><strong>维妮孙悟空</strong><strong></strong></p>
</td>
<td valign="top" width="142">
<p><strong>芭比娃娃</strong><strong></strong></p>
</td>
</tr>
<tr>
<td valign="top" width="142">
<p><strong>最小可能重量</strong><strong></strong></p>
</td>
<td valign="top" width="142">
<p>1</p>
</td>
<td valign="top" width="142">
<p>2</p>
</td>
<td valign="top" width="142">
<p>3</p>
</td>
</tr>
<tr>
<td valign="top" width="142">
<p><strong>最大可能重量</strong><strong></strong></p>
</td>
<td valign="top" width="142">
<p>3</p>
</td>
<td valign="top" width="142">
<p>4</p>
</td>
<td valign="top" width="142">
<p>5</p>
</td>
</tr>
</tbody>
</table>
<p>表1. 玩具和它们的最小、最大可能重量</p>
<p> </p>
<p>这些范围太粗略，冰冰希望能把它们缩小一些。</p>
<p>正好佳佳有一个电子天平，不仅可以告诉你左右两边是否一样重，还可以告诉你左边比右边重（或轻）多少。天平很大，左右两边都可以放任意多件玩具。</p>
<p>冰冰向佳佳借电子天平，希望能算出每个玩具的精确重量。佳佳为了考验冰冰，只允许她把任意一个玩具往天平的左侧和右侧最多各放一次。例如，如果她曾经把皮卡秋放在天平的左侧，则她不能再次把它放在天平的左侧。冰冰同意了。她一共称量了两次，结果如下（数字表示左边比右边重多少）：</p>
<p>根据结果和表1，可以确定三个玩具的重量一定是3，4，3，也就是说，通过称量结果所得到的更新后的重量范围是：</p>
<table border="0" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="142">
<p><strong> </strong></p>
</td>
<td valign="top" width="142">
<p><strong>皮卡秋</strong><strong></strong></p>
</td>
<td valign="top" width="142">
<p><strong>维妮孙悟空</strong><strong></strong></p>
</td>
<td valign="top" width="142">
<p><strong>芭比娃娃</strong><strong></strong></p>
</td>
</tr>
<tr>
<td valign="top" width="142">
<p><strong>最小可能重量</strong><strong></strong></p>
</td>
<td valign="top" width="142">
<p>3</p>
</td>
<td valign="top" width="142">
<p>4</p>
</td>
<td valign="top" width="142">
<p>3</p>
</td>
</tr>
<tr>
<td valign="top" width="142">
<p><strong>最大可能重量</strong><strong></strong></p>
</td>
<td valign="top" width="142">
<p>3</p>
</td>
<td valign="top" width="142">
<p>4</p>
</td>
<td valign="top" width="142">
<p>3</p>
</td>
</tr>
</tbody>
</table>
<p>表2. 根据称量结果所得到的精确范围</p>
<p> </p>
<p>冰冰以后还会买很多很多玩具，她不想每次都自己计算每个玩具的重量。她需要写一个程序计算每个玩具最精确的重量下限和上限，你能帮她吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件第一行包含两个整数<em>n</em>和<em>m</em>，即玩具的个数和称量的次数。第二行包含2<em>n</em>个数，第2<em>i</em>-1个数和第2<em>i</em>个数分别表示第<em>i</em>个玩具的重量初始下限和初始上限。以下<em>m</em>行，每行前三个数<em>L</em>，<em>R</em>，<em>D</em>表示左边的玩具数、右边的玩具数和左右两边的重量差(<em>L</em>, <em>R</em>&gt;=0)，接下来的<em>L</em>个数为天平左边的玩具编号，再接下来的<em>R</em>个数为天平右边的玩具编号。输入保证每个玩具在天平的每一边最多出现一次。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;&nbsp;输出文件包含2<em>n</em>个整数，第2<em>i</em>-1个数和第2<em>i</em>个数分别表示第<em>i</em>个玩具的重量下限和上限，即最小可能的整数重量和最大可能的整数重量。如果无解（可能是天平坏了），只输出一个数-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2</p>
<p>1 3 2 4 3 5</p>
<p>1 1 -1 1 2</p>
<p>1 1 1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 3 4 4 3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3&lt;=<em>n</em>&lt;=200, 1&lt;=<em>m</em>&lt;=100，重量上限不超过20000。</p>
<p>50%的数据满足3&lt;=<em>n</em>&lt;=10，1&lt;=<em>m</em>&lt;=5。</p>
</div>
</div>