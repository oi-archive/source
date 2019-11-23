<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>阿兰是某机密部门的打字员，她现在接到一个任务：需要在一天之内输入几百个长度固定为6的密码。当然，她希望输入的过程中敲击键盘的总次数越少越好。</p>
<p>不幸的是，出于保密的需要，该部门用于输入密码的键盘是特殊设计的，键盘上没有数字键，而只有以下六个键：Swap0, Swap1, Up, Down, Left, Right，为了说明这6个键的作用，我们先定义录入区的6个位置的编号，从左至右依次为1，2，3，4，5，6。下面列出每个键的作用：</p>
<p>Swap0：按Swap0，光标位置不变，将光标所在位置的数字与录入区的1号位置的数字（左起第一个数字）交换。如果光标已经处在录入区的1号位置，则按Swap0键之后，录入区的数字不变；</p>
<p>Swap1：按Swap1，光标位置不变，将光标所在位置的数字与录入区的6号位置的数字（左起第六个数字）交换。如果光标已经处在录入区的6号位置，则按Swap1键之后，录入区的数字不变；</p>
<p>Up：按Up，光标位置不变，将光标所在位置的数字加1（除非该数字是9）。例如，如果光标所在位置的数字为2，按Up之后，该处的数字变为3；如果该处数字为9，则按Up之后，数字不变，光标位置也不变；</p>
<p>Down：按Down，光标位置不变，将光标所在位置的数字减1（除非该数字是0），如果该处数字为0，则按Down之后，数字不变，光标位置也不变；</p>
<p>Left：按Left，光标左移一个位置，如果光标已经在录入区的1号位置（左起第一个位置）上，则光标不动；</p>
<p>Right：按Right，光标右移一个位置，如果光标已经在录入区的6号位置（左起第六个位置）上，则光标不动。</p>
<p>当然，为了使这样的键盘发挥作用，每次录入密码之前，录入区总会随机出现一个长度为6的初始密码，而且光标固定出现在1号位置上。当巧妙地使用上述六个特殊键之后，可以得到目标密码，这时光标允许停在任何一个位置。</p>
<p>现在，阿兰需要你的帮助，编写一个程序，求出录入一个密码需要的最少的击键次数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件仅一行，含有两个长度为6的数，前者为初始密码，后者为目标密码，两个密码之间用一个空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>文件仅一行，含有一个正整数，为最少需要的击键次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>123456</p>
<p>654321</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>时间限制应该是8s。</p>
<p>初始密码是123456，光标停在数字1上。对应上述最少击键次数的击键序列为：</p>
<p> </p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="187">
<p>击键序列：</p>
</td>
<td valign="top" width="276">
<p>击键后的录入区</p>
<p>（下划线表示光标所在位置）</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p> </p>
</td>
<td valign="top" width="276">
<p><span style="text-decoration: underline;">1</span>23456</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Swap1</p>
</td>
<td valign="top" width="276">
<p><span style="text-decoration: underline;">6</span>23451</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Right</p>
</td>
<td valign="top" width="276">
<p>6<span style="text-decoration: underline;">2</span>3451</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Swap0</p>
</td>
<td valign="top" width="276">
<p>2<span style="text-decoration: underline;">6</span>3451</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Down</p>
</td>
<td valign="top" width="276">
<p>2<span style="text-decoration: underline;">5</span>3451</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Right</p>
</td>
<td valign="top" width="276">
<p>25<span style="text-decoration: underline;">3</span>451</p>
</td>
</tr>
</tbody>
</table>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="187">
<p>Up</p>
</td>
<td valign="top" width="276">
<p>25<span style="text-decoration: underline;">4</span>451</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Right</p>
</td>
<td valign="top" width="276">
<p>254<span style="text-decoration: underline;">4</span>51</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Down</p>
</td>
<td valign="top" width="276">
<p>254<span style="text-decoration: underline;">3</span>51</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Right</p>
</td>
<td valign="top" width="276">
<p>2543<span style="text-decoration: underline;">5</span>1</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Up</p>
</td>
<td valign="top" width="276">
<p>2543<span style="text-decoration: underline;">6</span>1</p>
</td>
</tr>
<tr>
<td valign="top" width="187">
<p>Swap0</p>
</td>
<td valign="top" width="276">
<p>6543<span style="text-decoration: underline;">2</span>1</p>
</td>
</tr>
</tbody>
</table>
<p>最少的击键次数为11。</p>
</div>
</div>