<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某校的惯例是在每学期的期末考试之后发放奖学金。发放的奖学金共有五种，获取的条件各自不同：<br><br>1)  院士奖学金，每人8000元，期末平均成绩高于80分（&gt;80），并且在本学期内发表1篇或1篇以上论文的学生均可获得；<br><br>2)  五四奖学金，每人4000元，期末平均成绩高于85分（&gt;85），并且班级评议成绩高于80分（&gt;80）的学生均可获得；<br><br>3)  成绩优秀奖，每人2000元，期末平均成绩高于90分（&gt;90）的学生均可获得；<br><br>4)  西部奖学金，每人1000元，期末平均成绩高于85分（&gt;85）的西部省份学生均可获得；<br><br>5)  班级贡献奖，每人850元，班级评议成绩高于80分（&gt;80）的学生干部均可获得；<br><br>只要符合条件就可以得奖，每项奖学金的获奖人数没有限制，每名学生也可以同时获得多项奖学金。例如姚林的期末平均成绩是87分，班级评议成绩82分，同时他还是一位学生干部，那么他可以同时获得五四奖学金和班级贡献奖，奖金总数是4850元。<br>现在给出若干学生的相关数据，请计算哪些同学获得的奖金总数最高（假设总有同学能满足获得奖学金的条件）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行是一个整数N（1&lt;=N&lt;=100），表示学生的总数。接下来的N行每行是一位学生的数据，从左向右依次是姓名，期末平均成绩，班级评议成绩，是否是学生干部，是否是西部省份学生，以及发表的论文数。姓名是由大小写英文字母组成的长度不超过20的字符串（不含空格）；期末平均成绩和班级评议成绩都是0到100之间的整数（包括0和100）；是否是学生干部和是否是西部省份学生分别用一个字符表示，Y表示是，N表示不是；发表的论文数是0到10的整数（包括0和10）。每两个相邻数据项之间用一个空格分隔。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包括共三行，第一行是获得最多奖金的学生的姓名，第二行是这名学生获得的奖金总数。如果有两位或两位以上的学生获得的奖金最多，输出他们之中在输入文件中出现最早的学生的姓名。第三行是这N个学生获得的奖学金的总数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style="">4<br>YaoLin 87 82 Y N 0<br>ChenRuiyi 88 78 N Y 1<br>LiXin 92 88 N N 0<br>ZhangQin 83 87 Y N 1<br><br></span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">ChenRuiyi<br>9000<br>28700</span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>