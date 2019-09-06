# 题目描述


<p>
大小各不相同的一队青蛙站在河左岸的石墩（记为A）上，要过到对岸的石墩(记为D)上去。河心有几片菏叶(分别记为Y1…Ym)和几个石墩(分别记为S1…Sn)。图示如下：
</p>
<p>
<img alt="Image:Frog.gif" src="../../mw/images/9/99/Frog.gif" height="206" border="0" width="402"/> 
</p>
<p>
青蛙的站队和移动方法规则如下：
</p>
<ol>
<li>
每只青蛙只能站在荷叶、石墩，或者仅比它大一号的青蛙背上（统称为合法的落脚点）；
</li>
<li>
一只青蛙只有背上没有其它青蛙的时候才能够从一个落脚点跳到另一个落脚点；
</li>
<li>
青蛙允许从左岸A直接跳到河心的石墩、荷叶和右岸的石墩D上，允许从河心的石墩和荷叶跳到右岸的石墩D上；
</li>
<li>
青蛙在河心的石墩之间、荷叶之间以及石墩和荷叶之间可以来回跳动；
</li>
<li>
青蛙在离开左岸石墩后，不能再返回左岸；到达右岸后，不能再跳回；
</li>
<li>
假定石墩承重能力很大，允许无论多少只青蛙都可呆在上面。但是，由于石墩的面积不大，至多只能有一只青蛙直接站在上面，而其他的青蛙只能依规则1落在比它大一号的青蛙的背上。
</li>
<li>
荷叶不仅面积不大，而且负重能力也有限，至多只能有一只青蛙站在上面。
</li>
<li>
每一步只能移动一只青蛙，并且移动后需要满足站队规则；
</li>
<li>
在一开始的时候，青蛙均站在A上，最大的一只青蛙直接站在石墩上，而其它的青蛙依规则6站在比其大一号的青蛙的背上。
</li>
</ol>
<p>
青蛙希望最终能够全部移动到D上，并完成站队。
</p>
<p>
设河心有m片荷叶和n个石墩，请求出这队青蛙至多有多少只，在满足站队和移动规则的前提下，能从A过到D。
</p>
<p>
例如，在m=1且 n=1时，河心有一片荷叶（Y1）和一个石墩（S1），此时至多有4只青蛙能够过河（由小到大称为1、2、3、4），过河的一种方法为：
</p>
<table style="border-collapse:collapse;" cellspacing="0" cellpadding="0" height="1088" border="1" width="570">
<tbody>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span style="font-family:宋体;">开始</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span> </span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>1</span> 
</p>
<p style="text-indent:0cm;">
<span>2</span> 
</p>
<p style="text-indent:0cm;">
<span>3</span> 
</p>
<p style="text-indent:0cm;">
<span>4</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 1</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>1 from A to Y<sub>1</sub></span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>2</span> 
</p>
<p style="text-indent:0cm;">
<span>3</span> 
</p>
<p style="text-indent:0cm;">
<span>4         1</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 2</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>2 from A to S<sub>1</sub></span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>3</span> 
</p>
<p style="text-indent:0cm;">
<span>4    2     1</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 3</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>1 from Y<sub>1</sub> to S<sub>1</sub></span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>3    1</span> 
</p>
<p style="text-indent:0cm;">
<span>4    2</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 4</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>3 from A to Y<sub>1</sub></span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>     1</span> 
</p>
<p style="text-indent:0cm;">
<span>4    2     3</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 5</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>4 from A to D</span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>     1</span> 
</p>
<p style="text-indent:0cm;">
<span>     2     3    4</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 6</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>3 from Y<sub>1</sub> to D</span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>     1         3</span> 
</p>
<p style="text-indent:0cm;">
<span>     2         4</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 7 </span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>1 from S<sub>1</sub> to Y<sub>1</sub></span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>              3</span> 
</p>
<p style="text-indent:0cm;">
<span>     2     1    4</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 8</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>2 from S<sub>1</sub> to D</span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:88.2pt;">
<span>    2</span> 
</p>
<p style="text-indent:88.2pt;">
<span>    3</span> 
</p>
<p style="text-indent:0cm;">
<span>         1     4</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p style="text-indent:0cm;">
<span>Step 9</span> 
</p>
</td>
<td valign="top" width="113">
<p style="text-indent:0cm;">
<span>1 from Y<sub>1</sub> to D</span> 
</p>
</td>
<td valign="top" width="159">
<p style="text-indent:0cm;">
<span>                 1</span> 
</p>
<p style="text-indent:0cm;">
<span>                 2</span> 
</p>
<p style="text-indent:0cm;">
<span>                 3</span> 
</p>
<p style="text-indent:0cm;">
<span>                 4</span> 
</p>
<p style="text-indent:0cm;">
<span>A    S<sub>1</sub>    Y<sub>1</sub>    D</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
此例中，当河心有一片荷叶和一个石墩时，4只青蛙能够跳动9步过河。
</p>
<p>
[输入文件]
</p>
<p>
文件仅有两行，每一行仅包含一个整数和一个换行/回车符。第一行的数字为河心的石墩数n（0&lt;=n&lt;=25），第二行为荷叶数m（0&lt;=m&lt;=25）。
</p>
<p>
[输出文件]
</p>
<p>
文件中仅包含一个数字和一个换行/回车符。该数字为在河心有n个石墩和m片荷叶时，最多能够过河的青蛙的只数。
</p>
<p>
[输入输出文件样例]
</p>
<p>
Input
</p>
<pre>1
1
</pre>
<p>
Output
</p>
<pre>4
</pre>
