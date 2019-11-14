<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    某银行的保险库收藏着多件珍贵的物品。为了保证物品的安全，除非有特别的原因，否则银行的保险库要全天24小时开启监控设备进行实时监控：当确实需要临时关闭监控设备时，需要使用为特定操作人员设计的监控密码，这种密码要与操作人员的指纹信息结合，生成一个符合规定的数据，该操作人员才能关闭银行的保险库的监控设备。于是银行的行长就找到了贝贝，请他帮忙设置一个系统判断输入的密码是否正确。密码要求如下：</p>
<p>  行长设想的监控密码是一个不超过9位的十进制正整数，且要有如下特征：它的各位数字之和等于该数的12进制表示的各位数字之和，还等于该数的16进制表示的各位数字之和。</p>
<p>    例如，2991的各位数字之和为2+9+9+1=21，因为2991=l×1728+8×144+9×12+3，它的12进制表示是1893<sub>12</sub>，各位数字之和也是21。但是2991的16进制表示是BAF<sub>16</sub>，并且11+10+15=36，所以2991不是合法的监控密码。</p>
<p>    又如，2992在全部三种表示法中各位数字之和都是22，所以2992是合法的监控密码。</p>
<p>    现在请你帮贝贝的忙，编一个程序判断输入的密码是否可以用作银行保险库的监控密码。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件只有一个长度不超过9位的十进制正整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp; 第1行为输入的十进制数所对应的十六进制数各位数字之和，第2行为&ldquo;Right&rdquo;（可用作监控密码）或&ldquo;Wrong&rdquo;（不可用作监控密码）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td width="139">
<p> </p>
</td>
<td width="188">
<p>输入</p>
</td>
<td width="188">
<p>输出</p>
</td>
</tr>
<tr>
<td width="139">
<p>样例1</p>
</td>
<td width="188">
<p>3</p>
</td>
<td width="188">
<p>3</p>
<p>Right</p>
</td>
</tr>
<tr>
<td width="139">
<p>样例2</p>
</td>
<td width="188">
<p>112</p>
</td>
<td width="188">
<p>7</p>
<p>Wrong</p>
</td>
</tr>
<tr>
<td width="139">
<p>样例3</p>
</td>
<td width="188">
<p>2992</p>
</td>
<td width="188">
<p>22</p>
<p>Right</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>在样例输入里</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>