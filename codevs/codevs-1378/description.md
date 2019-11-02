<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>学校实行学分制。每门的必修课都有固定的学分，同时还必须获得相应的选修课程学分。学校开设了N（N&lt;300）门的选修课程，每个学生可选课程的数量M是给定的。学生选修了这M门课并考核通过就能获得相应的学分。 <br><br> 　　在选修课程中，有些课程可以直接选修，有些课程需要一定的基础知识，必须在选了其它的一些课程的基础上才能选修。例如《Frontpage》必须在选修了《Windows操作基础》之后才能选修。我们称《Windows操作基础》是《Frontpage》的先修课。每门课的直接先修课最多只有一门。两门课也可能存在相同的先修课。每门课都有一个课号，依次为1，2，3，…。 例如: <br><br>【详见图片】<br> 表中1是2的先修课，2是3、4的先修课。如果要选3，那么1和2都一定已被选修过。 　　你的任务是为自己确定一个选课方案，使得你能得到的学分最多，并且必须满足先修课优先的原则。假定课程之间不存在时间上的冲突。</p>

<img src="/source/codevs/codevs-1378/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMzc4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMzc4LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行包括两个整数N、M（中间用一个空格隔开）其中1≤N≤300,1≤M≤N。 <br> 以下N行每行代表一门课。课号依次为1，2，…，N。每行有两个数（用一个空格隔开），第一个数为这门课先修课的课号（若不存在先修课则该项为0），第二个数为这门课的学分。学分是不超过10的正整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只有一个数,实际所选课程的学分总数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 4<br>2 2<br>0 1<br>0 4<br>2 1<br>7 1<br>7 6<br>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>各个测试点1s</p>
</div>
</div>