<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Freda和Rainbow来到了魔力铁路的1号站台。它们知道，魔力铁路不同于普通的铁路，下面有一段关于魔力铁路的介绍。</p>
<p>魔力铁路一共有N座站台，从第i(1&lt;i&lt;=N)号站台出发可以到达第i-1号站台。同时，对于每个i(1&lt;=i&lt;=N)，你需要规定x[i]为1~N当中的任意一个数字，表示从第i号站台出发可以到达的另外一个站台，当然，你也可以把x[i]规定为i或者i-1。</p>
<p>Rainbow和Freda想知道，有多少种不同的规定x[i]的方案，使得它们能够到达N号站台呢？方案A、B不同的条件是：存在一个i（1&lt;=i&lt;=N）使得方案A中的x[i]与方案B中的x[i]不同。Freda最讨厌乱七八糟的上万位数字了，所以，记得把答案mod 1000000007（10^9+7）哦lala~</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行一个整数N，表示站台的总数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数Ans，表示Freda和Rainbow能够到达N号站台的方案数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释</p>
<p>12种可能的方案如下(每行代表一种方案)：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="57">
<p>x[1]</p>
</td>
<td valign="top" width="47">
<p>x[2]</p>
</td>
<td valign="top" width="57">
<p>x[3]</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>2</p>
</td>
<td valign="top" width="47">
<p>3</p>
</td>
<td valign="top" width="57">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>2</p>
</td>
<td valign="top" width="47">
<p>3</p>
</td>
<td valign="top" width="57">
<p>2</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>2</p>
</td>
<td valign="top" width="47">
<p>3</p>
</td>
<td valign="top" width="57">
<p>3</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>1</p>
</td>
<td valign="top" width="57">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>1</p>
</td>
<td valign="top" width="57">
<p>2</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>1</p>
</td>
<td valign="top" width="57">
<p>3</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>2</p>
</td>
<td valign="top" width="57">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>2</p>
</td>
<td valign="top" width="57">
<p>2</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>2</p>
</td>
<td valign="top" width="57">
<p>3</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>3</p>
</td>
<td valign="top" width="57">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>3</p>
</td>
<td valign="top" width="57">
<p>2</p>
</td>
</tr>
<tr>
<td valign="top" width="57">
<p>3</p>
</td>
<td valign="top" width="47">
<p>3</p>
</td>
<td valign="top" width="57">
<p>3</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>数据范围与约定</p>
<p>对于30%的数据，N&lt;=5.</p>
<p>对于50%的数据，N&lt;=10.</p>
<p>对于70%的数据，N&lt;=100.</p>
<p>对于100%的数据，0&lt;N&lt;=5000.</p>
</div>
</div>