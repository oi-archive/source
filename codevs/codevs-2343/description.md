<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> </p>
<p>有一个<em>n</em>个元素的数组，每个元素初始均为0。有<em>m</em>条指令，要么让其中一段连续序列数字反转——0变1，1变0（操作1），要么询问某个元素的值（操作2）。例如当<em>n</em>=20时，10条指令如下：</p>
<p> </p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="111">
<p><strong>操作</strong><strong></strong></p>
</td>
<td valign="top" width="112">
<p><strong>回答</strong><strong></strong></p>
</td>
<td valign="top" width="216">
<p><strong>操作后的数组</strong><strong></strong></p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>1 1 10</p>
</td>
<td valign="top" width="112">
<p>N/A</p>
</td>
<td valign="top" width="216">
<p>11111111110000000000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>2 6</p>
</td>
<td valign="top" width="112">
<p>1</p>
</td>
<td valign="top" width="216">
<p>11111<strong><span style="text-decoration: underline;">1</span></strong>11110000000000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>2 12</p>
</td>
<td valign="top" width="112">
<p>0</p>
</td>
<td valign="top" width="216">
<p>11111111110<strong><span style="text-decoration: underline;">0</span></strong>00000000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>1 5 12</p>
</td>
<td valign="top" width="112">
<p>N/A</p>
</td>
<td valign="top" width="216">
<p>11110000001100000000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>2 6</p>
</td>
<td valign="top" width="112">
<p>0</p>
</td>
<td valign="top" width="216">
<p>11110<strong><span style="text-decoration: underline;">0</span></strong>00001100000000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>2 15</p>
</td>
<td valign="top" width="112">
<p>0</p>
</td>
<td valign="top" width="216">
<p>11110000001100<strong><span style="text-decoration: underline;">0</span></strong>00000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>1 6 16</p>
</td>
<td valign="top" width="112">
<p>N/A</p>
</td>
<td valign="top" width="216">
<p>11110111110011110000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>1 11 17</p>
</td>
<td valign="top" width="112">
<p>N/A</p>
</td>
<td valign="top" width="216">
<p>11110111111100001000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>2 12</p>
</td>
<td valign="top" width="112">
<p>1</p>
</td>
<td valign="top" width="216">
<p>11110111111<strong><span style="text-decoration: underline;">1</span></strong>00001000</p>
</td>
</tr>
<tr>
<td valign="top" width="111">
<p>2 6</p>
</td>
<td valign="top" width="112">
<p>1</p>
</td>
<td valign="top" width="216">
<p>11110<strong><span style="text-decoration: underline;">1</span></strong>11111100001000</p>
</td>
</tr>
</tbody>
</table>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个整数<em>n</em>，<em>m</em>，表示数组的长度和指令的条数，以下<em>m</em>行，每行的第一个数<em>t</em>表示操作的种类。若<em>t</em>=1，则接下来有两个数<em>L</em>, <em>R</em> (<em>L</em>&lt;=<em>R</em>)，表示区间[<em>L</em>, <em>R</em>]的每个数均反转；若<em>t</em>=2，则接下来只有一个数<em>I</em>，表示询问的下标。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每个操作2输出一行（非0即1），表示每次操作2的回答。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>20 10</p>
<p>1 1 10</p>
<p>2 6</p>
<p>2 12</p>
<p>1 5 12</p>
<p>2 6</p>
<p>2 15</p>
<p>1 6 16</p>
<p>1 11 17</p>
<p>2 12</p>
<p>2 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>0</p>
<p>0</p>
<p>0</p>
<p>1</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足：1&lt;=<em>n</em>&lt;=1,000，1&lt;=<em>m</em>&lt;=10,000</p>
<p>100%的数据满足：1&lt;=<em>n</em>&lt;=100,000，1&lt;=<em>m</em>&lt;=500,000</p>
</div>
</div>