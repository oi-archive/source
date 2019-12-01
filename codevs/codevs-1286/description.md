<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>OIER<span style="">公司是一家大型专业化软件公司，有着数以万计的员工。作为一名出纳员，我的任务之一便是统计每位员工的工资。这本来是一份不错的工作，但是令人郁闷的是，我们的老板反复无常，经常调整员工的工资。如果他心情好，就可能把每位员工的工资加上一个相同的量。反之，如果心情不好，就可能把他们的工资扣除一个相同的量。我真不知道除了调工资他还做什么其它事情。</span></p>
<p>工资的频繁调整很让员工反感，尤其是集体扣除工资的时候，一旦某位员工发现自己的工资已经低于了合同规定的工资下界，他就会立刻气愤地离开公司，并且再也不会回来了。每位员工的工资下界都是统一规定的。每当一个人离开公司，我就要从电脑中把他的工资档案删去，同样，每当公司招聘了一位新员工，我就得为他新建一个工资档案。</p>
<p>老板经常到我这边来询问工资情况，他并不问具体某位员工的工资情况，而是问现在工资第k多的员工拿多少工资。每当这时，我就不得不对数万个员工进行一次漫长的排序，然后告诉他答案。</p>
<p>好了，现在你已经对我的工作了解不少了。正如你猜的那样，我想请你编一个工资统计程序。怎么样，不是很困难吧？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个非负整数n和min。n表示下面有多少条命令，min表示工资下界。</p>
<p>接下来的n行，每行表示一条命令。命令可以是以下四种之一：</p>
<table>
<tbody>
<tr>
<td valign="top" width="79">
<p>名称</p>
</td>
<td valign="top" width="72">
<p>格式</p>
</td>
<td valign="top" width="380">
<p>作用</p>
</td>
</tr>
<tr>
<td valign="top" width="79">
<p>I<span style="">命令</span></p>
</td>
<td valign="top" width="72">
<p>I_k</p>
</td>
<td valign="top" width="380">
<p>新建一个工资档案，初始工资为k。如果某员工的初始工资低于工资下界，他将立刻离开公司。</p>
</td>
</tr>
<tr>
<td valign="top" width="79">
<p>A<span style="">命令</span></p>
</td>
<td valign="top" width="72">
<p>A_k</p>
</td>
<td valign="top" width="380">
<p>把每位员工的工资加上k</p>
</td>
</tr>
<tr>
<td valign="top" width="79">
<p>S<span style="">命令</span></p>
</td>
<td valign="top" width="72">
<p>S_k</p>
</td>
<td valign="top" width="380">
<p>把每位员工的工资扣除k</p>
</td>
</tr>
<tr>
<td valign="top" width="79">
<p>F<span style="">命令</span></p>
</td>
<td valign="top" width="72">
<p>F_k</p>
</td>
<td valign="top" width="380">
<p>查询第k多的工资</p>
</td>
</tr>
</tbody>
</table>
<p>_<span style="">（下划线）表示一个空格，</span><span style="font-family: 'Times New Roman';">I</span><span style="">命令、</span><span style="font-family: 'Times New Roman';">A</span><span style="">命令、</span><span style="font-family: 'Times New Roman';">S</span><span style="">命令中的</span>k是一个非负整数，<span style="font-family: 'Times New Roman';">F</span><span style="">命令中的</span>k是一个正整数。</p>
<p>在初始时，可以认为公司里一个员工也没有。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件的行数为<span style="font-family: 'Times New Roman';">F</span><span style="font-family: 宋体;">命令的条数加一。</span></p>
<p class="p0">对于每条<span style="font-family: 'Times New Roman';">F</span><span style="font-family: 宋体;">命令，你的程序要输出一行，仅包含一个整数，为当前工资第</span>k多的员工所拿的工资数，如果k大于目前员工的数目，则输出<span style="font-family: 'Times New Roman';">-1</span><span style="font-family: 宋体;">。</span></p>
<p class="p0">输出文件的最后一行包含一个整数，为离开公司的员工的总数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 10</p>
<p>I 60</p>
<p>I 70</p>
<p>S 50</p>
<p>F 2</p>
<p>I 30</p>
<p>S 15</p>
<p>A 5</p>
<p>F 1</p>
<p>F 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>
<p>20</p>
<p>-1</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【约定】</p>
<p>l I<span style="">命令的条数不超过</span><span style="font-family: 'Times New Roman';">100000</span></p>
<p>l A<span style="">命令和</span><span style="font-family: 'Times New Roman';">S</span><span style="">命令的总条数不超过</span><span style="font-family: 'Times New Roman';">100</span></p>
<p>l F<span style="">命令的条数不超过</span><span style="font-family: 'Times New Roman';">100000</span></p>
<p>l 每次工资调整的调整量不超过<span style="font-family: 'Times New Roman';">1000</span></p>
<p>l 新员工的工资不超过<span style="font-family: 'Times New Roman';">100000</span></p>
</div>
</div>