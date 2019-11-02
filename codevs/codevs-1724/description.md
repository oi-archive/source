<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>学校为了控制作业量，实施“轻负担，高质量”的有效教学，对所有在校学生的作业量情况进行了调查。每个学生对每门课的日均作业时间进行评估。最后统计出每门课的日均作业时间的平均值，作为学校评价习题教学效果的一个重要参考。</p>
<p>为了避免个别学生不客观评估的影响，学生的评估值必须为1至100间的正整数，如果某个评估值为不在此范围内的整数，则忽略。现在要求完成：</p>
<p>(1)统计出每门课的日均作业时间的平均值;</p>
<p>(2)除去每门课中作业时间最多的和最少的<strong><em><span style="text-decoration: underline;">10%</span></em></strong>的学生(<strong><em><span style="text-decoration: underline;">四舍五入</span></em></strong>)后，统计平均值。</p>
<p>   请你写个程序，完成以上任务。(提示:Pascal语言中, Round(x)为四舍五入函数,在C语言中可使用int(x+0.5))</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件count.in 的第1行有2个正整数n,m(以一个空格分隔)。表示有n个人,m门课。</p>
<p>第2行至第n+1行，每行有m个正整数，表示学生对每门课日均作业时间的评估，每个整数之间以一个空格分隔。其中：第k+1行的第j个数表示第k个学生填写的第j门课的日均作业时间；</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>出文件count.out有2行，每行有m个数（保留2位小数，每行的各个数之间以一个空格相互分隔），表示每门课日均作业时间的平均值。其中：</p>
<p>第1行的第j个数表示所有合法填写学生的第j门课的日均作业时间的平均值；</p>
<p>第2行的第j个数表示除去10%最多合法时间和10%最少合法时间的学生后，所有合法填写学生第j门课的日均作业时间的平均值；</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> </p>
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td height="79" width="129">
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td>
<div>
<p> </p>
</div>
</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
<p>7 2</p>
<p>10 11</p>
<p>60 69</p>
<p>70 73</p>
<p>80 87</p>
<p>90 91</p>
<p>100 100</p>
<p>110 100</p>
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td height="99" width="536">
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td>
<div>
<p> </p>
</div>
</td>
</tr>
</tbody>
</table>
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
<p> </p>
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td height="79" width="129">
<table cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td>
<div>
<p>【样例输出】</p>
<p>68.33 75.86</p>
<p>75.00 84.00</p>
</div>
</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>

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