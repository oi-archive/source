<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong><span style="text-decoration: underline;">大小各不相同</span></strong>的一队青蛙站在河左岸的石墩（记为A）上，要过到对岸的石墩(记为D)上去。河心有几片菏叶(分别记为Y<sub>1</sub>…Y<sub>m</sub>)和几个石墩(分别记为S<sub>1</sub>…S<sub>n</sub>)。</p>
<p>青蛙的站队和移动方法规则如下：</p>
<p>1．                        每只青蛙只能站在荷叶、石墩，或者<strong><span style="text-decoration: underline;">仅比它大一号</span></strong>的青蛙背上（统称为合法的落脚点）；</p>
<p>2．                        一只青蛙只有背上没有其它青蛙的时候才能够从一个落脚点跳到另一个落脚点；</p>
<p>3．                        青蛙允许从左岸A直接跳到河心的石墩、荷叶和右岸的石墩D上，允许从河心的石墩和荷叶跳到右岸的石墩D上；</p>
<p>4．                        青蛙在河心的石墩之间、荷叶之间以及石墩和荷叶之间可以来回跳动；</p>
<p>5．                        青蛙在离开左岸石墩后，不能再返回左岸；到达右岸后，不能再跳回；</p>
<p>6．                        假定石墩承重能力很大，允许无论多少只青蛙都可呆在上面。但是，由于石墩的面积不大，至多只能有一只青蛙直接站在上面，而其他的青蛙只能依规则1落在比它大一号的青蛙的背上。</p>
<p>7．                        荷叶不仅面积不大，而且负重能力也有限，至多只能有一只青蛙站在上面。</p>
<p>8．                        每一步只能移动一只青蛙，并且移动后需要满足站队规则；</p>
<p>9．                        在一开始的时候，青蛙均站在A上，最大的一只青蛙直接站在石墩上，而其它的青蛙依规则6站在比其大一号的青蛙的背上。</p>
<p>青蛙希望最终能够全部移动到D上，并完成站队。</p>
<p>设河心有m片荷叶和n个石墩，请求出这队青蛙至多有多少只，在满足站</p>
<p>队和移动规则的前提下，能从A过到D。</p>
<p>例如，在m=1且 n=1时，河心有一片荷叶（Y<sub>1</sub>）和一个石墩（S<sub>1</sub>），此时至多有4只青蛙能够过河（由小到大称为1、2、3、4），过河的一种方法为：</p>
<div>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="67">
<p>开始</p>
</td>
<td valign="top" width="113">
<p> </p>
</td>
<td valign="top" width="159">
<p>1</p>
<p>2</p>
<p>3</p>
<p>4</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 1</p>
</td>
<td valign="top" width="113">
<p>1 from A to Y<sub>1</sub></p>
</td>
<td valign="top" width="159">
<p>2</p>
<p>3</p>
<p>4           1</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 2</p>
</td>
<td valign="top" width="113">
<p>2 from A to S<sub>1</sub></p>
</td>
<td valign="top" width="159">
<p>3</p>
<p>4    2     1</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 3</p>
</td>
<td valign="top" width="113">
<p>1 from Y<sub>1</sub> to S<sub>1</sub></p>
</td>
<td valign="top" width="159">
<p>3    1</p>
<p>4    2</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 4</p>
</td>
<td valign="top" width="113">
<p>3 from A to Y<sub>1</sub></p>
</td>
<td valign="top" width="159">
<p>     1</p>
<p>4    2     3</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 5</p>
</td>
<td valign="top" width="113">
<p>4 from A to D</p>
</td>
<td valign="top" width="159">
<p>     1</p>
<p>     2     3     4</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 6</p>
</td>
<td valign="top" width="113">
<p>3 from Y<sub>1</sub> to D</p>
</td>
<td valign="top" width="159">
<p>     1           3</p>
<p>     2           4</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 7</p>
</td>
<td valign="top" width="113">
<p>1 from S<sub>1</sub> to Y<sub>1</sub></p>
</td>
<td valign="top" width="159">
<p>                 3</p>
<p>     2     1     4</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 8</p>
</td>
<td valign="top" width="113">
<p>2 from S<sub>1</sub> to D</p>
</td>
<td valign="top" width="159">
<p>2</p>
<p>3</p>
<p>           1     4</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
<tr>
<td valign="top" width="67">
<p>Step 9</p>
</td>
<td valign="top" width="113">
<p>1 from Y<sub>1</sub> to D</p>
</td>
<td valign="top" width="159">
<p>                 1</p>
<p>                 2</p>
<p>                 3</p>
<p>                 4</p>
<p>A    S<sub>1</sub>    Y<sub>1</sub>    D</p>
</td>
</tr>
</tbody>
</table>
<p>此例中，当河心有一片荷叶和一个石墩时，4只青蛙能够跳动9步过河。</p>
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
<p>文件仅有两行，每一行仅包含一个整数和一个换行/回车符。第一行的数字为河心的石墩数n（0&lt;=n&lt;=25），第二行为荷叶数m（0&lt;=m&lt;=25）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>文件中仅包含一个数字和一个换行/回车符。该数字为在河心有n个石墩和m片荷叶时，最多能够过河的青蛙的只数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

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