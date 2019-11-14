<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一条项链由<span style="font-family: 'Times New Roman';">N</span><span style="">个珠子连接而成，编号依次为</span><span style="font-family: 'Times New Roman';">0, 1, 2, </span>…, N-1。每个珠子的颜色用0~9之间的一位数字来表示（因此，可用的颜色一共有<span style="font-family: 'Times New Roman';">10</span><span style="">种）。一条长度为</span><span style="font-family: 'Times New Roman';">4</span><span style="">的项链如下图所示：（圆圈中的数字表示颜色，圆圈旁边的数字为珠子的编号）</span></p>
<p> </p>
<p>需要注意的是，如图<span style="font-family: 'Times New Roman';">1</span><span style="">所示，编号为</span><span style="font-family: 'Times New Roman';">0, 1, 2</span>, …, N-1的珠子大小是依次递增的，设编号为i的珠子的颜色值为ai，则数字序列a0a1…an-1可以唯一的表示一种项链。例如，图<span style="font-family: 'Times New Roman';">1</span><span style="">所示的项链表示为“</span><span style="font-family: 'Times New Roman';">1337</span><span style="">”。</span></p>
<p> </p>
<p>现在有一台自动生产项链的机器，它的结构和工作方式如下所述：</p>
<p>机器的核心控制部件主要包括：一个CPU、一个整数寄存器START、和存储器S。</p>
<p> </p>
<p>机器内部固化有一段程序，由CPU解释执行。该程序的输入是长度为N的十进制数字序列<span style="font-family: 'Times New Roman';">A</span><span style="">，输出是另一个长度为</span><span style="font-family: 'Times New Roman';">N</span><span style="">的十进制数字序列</span>B。每次执行程序前将<span style="font-family: 'Times New Roman';">S</span><span style="">初始化为输入序列</span><span style="font-family: 'Times New Roman';">A</span><span style="">；程序结束后把</span><span style="font-family: 'Times New Roman';">S</span><span style="">作为输出串</span>B。START初始化为<span style="font-family: 'Times New Roman';">0</span><span style="">。</span></p>
<p>程序包含M条指令，顺序编号为<span style="font-family: 'Times New Roman';">1</span>~M<span style="">。指令共有</span><span style="font-family: 'Times New Roman';">5</span><span style="">种，以下是指令的格式和功能：（尖括号</span>&lt;&gt;表示指令参数，都是整数）</p>
<p> </p>
<table>
<tbody>
<tr>
<td valign="top" width="43">
<p>编号</p>
</td>
<td valign="top" width="48">
<p>功能</p>
</td>
<td valign="top" width="180">
<p>格式</p>
</td>
<td valign="top" width="296">
<p>说明</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>1</p>
</td>
<td valign="top" width="48">
<p>设置寄存器</p>
</td>
<td valign="top" width="180">
<p>SETSTART &lt;a&gt; &lt;b&gt;</p>
</td>
<td valign="top" width="296">
<p>设置<span style="font-family: 'Times New Roman';">START</span><span style="">的值：从</span><span style="font-family: 'Times New Roman';">S</span><span style="">的第</span>a位开始取连续b位得到的十进制整数（可能大于N-1）。</p>
<p>0&lt;=a&lt;=N-1<span style="">，</span><span style="font-family: 'Times New Roman';">1&lt;=b&lt;=min(8, N)</span></p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>2</p>
</td>
<td valign="top" width="48">
<p>循环移位</p>
</td>
<td valign="top" width="180">
<p>SHIFT &lt;L&gt; &lt;x&gt;</p>
</td>
<td valign="top" width="296">
<p>把<span style="font-family: 'Times New Roman';">S</span><span style="">从第</span>START位开始的连续<span style="font-family: 'Times New Roman';">L</span> 位，循环移位|x|位。x&gt;0时右移，x&lt;0时左移。</p>
<p>2&lt;=L&lt;=min(10, N)，1&lt;=|x|&lt;=L-1</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>3</p>
</td>
<td valign="top" width="48">
<p>乘法</p>
</td>
<td valign="top" width="180">
<p>MUL &lt;L&gt; &lt;x&gt;</p>
</td>
<td valign="top" width="296">
<p>把<span style="font-family: 'Times New Roman';">S</span><span style="">从第</span>START位开始的连续L位当做原始串（<span style="font-family: 'Times New Roman';">L</span>位十进制整数），将其乘以x以后保留结果的最低L位，替换原始串。</p>
<p>1&lt;=x&lt;=9，1&lt;=L&lt;=min(10, N)</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>4</p>
</td>
<td valign="top" width="48">
<p>条件</p>
</td>
<td valign="top" width="180">
<p>ONDIGIT &lt;x&gt; &lt;y&gt; &lt;z&gt;</p>
</td>
<td valign="top" width="296">
<p>如果S的第x位等于y，则跳转到第z条指令。</p>
<p>0&lt;=x&lt;=N-1<span style="">，</span><span style="font-family: 'Times New Roman';">0&lt;=y&lt;=9</span><span style="">，</span><span style="font-family: 'Times New Roman';">1&lt;=z&lt;=M</span>。z大于当前指令序号<span style="font-family: 'Times New Roman';">, </span><span style="">即不会往回跳转。</span></p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>5</p>
</td>
<td valign="top" width="48">
<p>终止</p>
</td>
<td valign="top" width="180">
<p>END</p>
</td>
<td valign="top" width="296">
<p>仅作为最后一条语句出现，程序终止。</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>由于项链是环型的，因此第i位和第i+kN位（k为整数）代表数字序列的同一位置。例如当N=4时，第6位和第<span style="font-family: 'Times New Roman';">2</span><span style="">位是等价的。</span></p>
<p> </p>
<p>下面是一个程序的例子：</p>
<table>
<tbody>
<tr>
<td valign="top" width="168">
<p>MUL 3 2</p>
<p>SETSTART 2 1</p>
<p>ONDIGIT 0 4 1</p>
<p>SHIFT 3 –2</p>
<p>END</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>机器启动的时候，输入一个数字串<span style="font-family: 'Times New Roman';">S</span>0，执行程序得到一个新的数字序列S1并生产出S1代表的项链来，以后机器每生产出一条新项链<span style="font-family: 'Times New Roman';">S</span>n，就把Sn对应的数字序列作为输入重新执行一遍程序，得到一个新的数字序列Sn+1并生产出新的项链。</p>
<p>由于长度为<span style="font-family: 'Times New Roman';">N</span><span style="">的项链种类数目是有限的（至多</span>10N种不同的项链），因此如果让机器一直工作下去，某些种类的项链会被生产出无限多条。编程计算出这些将被无限生产出的项链有多少种。在本题中，可以被生产出来的项链种类总数保证不超过106。</p>

<img src="/source/codevs/codevs-1677/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNjc3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTY3Ny5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行包含两个整数N和<span style="font-family: 'Times New Roman';">M</span> (1&lt;=N&lt;=100,000，2&lt;=M&lt;=30)<span style="">，第</span>2行包含一个有<span style="font-family: 'Times New Roman';">N</span><span style="">个数字的串</span>S0。第<span style="font-family: 'Times New Roman';">3</span><span style="">行到第</span>M+2行为一段程序，每行一条指令，程序保证无错，行末和行首均没有空格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">仅有一行，包含一个整数，是将被无限生产出来的项链种类数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<table>
<tbody>
<tr>
<td valign="top" width="284">
<p>4 5</p>
<p>1234</p>
<p>MUL 3 2</p>
<p>SETSTART 2 1</p>
<p>ONDIGIT 0 4 1</p>
<p>SHIFT 3 –2</p>
<p>END</p>
</td>
<td valign="top" width="284">
<p> </p>
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
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p>
<p>该样例对应于题目描述中给出的示例程序。前<span style="font-family: 'Times New Roman';">29</span><span style="">次生产出来的项链是：</span></p>
<p>4426 4886  6796  8356  0676  4136  6286  6526 4306  0866 </p>
<p>6712  2432  4882  2796  8556  0716  6412  2822  4562  2192</p>
<p>2786  6556  0316  6602  0322 4062 2182 4382  2786…</p>
<p>可以看出，从<span style="font-family: 'Times New Roman';">2786</span><span style="">开始机器陷入了循环，因此从</span><span style="font-family: 'Times New Roman';">2786</span><span style="">开始的</span><span style="font-family: 'Times New Roman';">8</span><span style="">条项链将被无限制的生产出来。</span></p>
</div>
</div>