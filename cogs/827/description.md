# 题目描述


<p>
</p><table class="ke-zeroborder" border="0">
<tbody>
<tr>
<td colspan="2">
描述 Description
</td>
<td rowspan="2">
<br/>
</td>
</tr>
<tr>
<td>
 
</td>
<td>
Tyvj的Admin--zhq同学将在寒假开始实行Tyvj new web计划，把Tyvj打造成为中国一流的信息学在线评测系统。Tyvj的new web计划里一共有n项，编号1~n，每项的重要度为v[i],Admin—zhq同学共工作m次，第j次从编号为l[j]~r[j]的项目里选择重要度最大的一项任务完成，所获得的进展量为(l[j]+r[j])*该任务的重要度。完成该任务后该任务的重要度变为0。请问Admin在工作m次后可以有多少进展量呢？<br/>
<br/>
注：数据保证初始情况下所有任务的重要度不同。
</td>
</tr>
</tbody>
</table>
<br/>
<br/>
<br/>
<br/>
<br/>
 <br/>
输入格式 Input Format<br/>
第一行为n，m<br/>
第二行n个整数v[i]。<br/>
接下来m行，每行两个整数l,r，表示Admin这一次将会从编号为l~r的项目里选择(包括l，r)重要度最大的来完成。
<p></p>
<p>
<br/>
<br/>
</p><table class="ke-zeroborder" border="0">
<tbody>
<tr>
<td colspan="2">
<br/>
输出格式 Output Format
</td>
<td rowspan="2">
<br/>
</td>
</tr>
<tr>
<td>
 
</td>
<td>
最终的进展量。由于结果可能会比较大，你只需要输出mod2011之后的结果即可。
</td>
</tr>
</tbody>
</table>
<p></p>
<p>
样例输入：
</p>
<p>
5 3<br/>
1 2 3 4 5<br/>
1 3<br/>
2 3<br/>
1 5
</p>
<div>
<br/>
</div>
<p>
<br/>
</p>
样例输出：
<p>
<br/>
</p>
<p>
52
</p>
<p>
<br/>
</p>
<p>
说明：
</p>
<p>
对于50%的数据，1&lt;=n,m&lt;=1000
</p>
<p>
对于100%的数据，1&lt;=n,m&lt;=200000,1&lt;=L&lt;=r&lt;=n,1&lt;=v[i]&lt;=100000
</p>
<p>
<br/>
</p>
