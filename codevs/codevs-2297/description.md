<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　受校门外的树这道经典问题的启发，A君根据基本的离散数学的知识，抽象出5种运算维护集合S(S初始为空)并最终输出S。现在，请你完成这道校门外的树之难度增强版——校门外的区间。</p>
<p> </p>
<p>　　5种运算如下：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="52">
<p>U T</p>
</td>
<td valign="top" width="82">
<p>S∪T</p>
</td>
</tr>
<tr>
<td valign="top" width="52">
<p>I T</p>
</td>
<td valign="top" width="82">
<p>S∩T</p>
</td>
</tr>
<tr>
<td valign="top" width="52">
<p>D T</p>
</td>
<td valign="top" width="82">
<p>S－T</p>
</td>
</tr>
<tr>
<td valign="top" width="52">
<p>C T</p>
</td>
<td valign="top" width="82">
<p>T－S</p>
</td>
</tr>
<tr>
<td valign="top" width="52">
<p>S T</p>
</td>
<td valign="top" width="82">
<p>S⊕T</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>　　基本集合运算如下：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="63">
<p>A∪B</p>
</td>
<td valign="top" width="171">
<p>{x : xÎA or xÎB}</p>
</td>
</tr>
<tr>
<td valign="top" width="63">
<p>A∩B</p>
</td>
<td valign="top" width="171">
<p>{x : xÎA and xÎB}</p>
</td>
</tr>
<tr>
<td valign="top" width="63">
<p>A－B</p>
</td>
<td valign="top" width="171">
<p>{x : xÎA and xÏB}</p>
</td>
</tr>
<tr>
<td valign="top" width="63">
<p>A⊕B</p>
</td>
<td valign="top" width="171">
<p>(A－B)∪(B－A)</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　输入共M行。</p>
<p>　　每行的格式为X T，用一个空格隔开，X表示运算的种类，T为一个区间(区间用(a,b), (a,b], [a,b), [a,b]表示)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　共一行，即集合S，各区间用空格隔开。若S为空则输出"empty set"。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>U [1,5]</p>
<p>D [3,3]</p>
<p>S [2,4]</p>
<p>C (1,5)</p>
<p>I (2,3]</p>
<p>U [4,6)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>(2,3) [4,6)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30% 的数据，0≤a≤b≤255，1≤M≤100</p>
<p>对于 100% 的数据，0≤a≤b≤65535，1≤M≤40000</p>
</div>
</div>