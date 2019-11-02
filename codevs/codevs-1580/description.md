<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    今天的英语课，王老师为了复习以前学过的单词，提高学生的学习兴趣，想了一个主意：</p>
<p>    (1)把全班分为n个小组，每个小组写一个学过的单词（均为小写）和一个整数k；</p>
<p>    (2)每个小组根据该单词中每个字母的字典顺序上推或下推k个位置，经过变换后得到一个新单词。推移规则是：如果k为正数则下推，否则上推，当推移超越边界时回到另一端继续推移。例如，单词为at，k=8则新单词为ib，字母t下移到边界z还不够，则再从第一个字母a开始继续推移。</p>
<p>    (3)每个小组把得到的新单词和整数k展示到黑板上；</p>
<p>    (4)王老师紧接着给出了一个字母，规定哪个小组最快完成以下任务则获胜：统计出该字母在所有小组开始写出的单词中出现的次数。</p>
<p>    你能编程帮助贝贝所在的小组获胜吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件共n+2行：</p>
<p>    第1行为王老师给出的一个字母；</p>
<p>    第2行为数字n(2≤n≤30)，表示全班分为n个小组；</p>
<p>    接着是n行，每行为每个小组得到的新单词(2≤单词长度≤14)，然后空一个格，后接一个整数k(-1000≤k≤1000)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp; 输出文件只有一个数，为给定字母在所有小组开始写出的单词中出现的次数。</p>

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
<p>e</p>
<p>2</p>
<p>welcome -2</p>
<p>happy 3</p>
</td>
<td width="188">
<p>2</p>
</td>
</tr>
<tr>
<td width="139">
<p>样例2</p>
</td>
<td width="188">
<p>t</p>
<p>2</p>
<p>school 50</p>
<p>teacher 3</p>
</td>
<td width="188">
<p>0</p>
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