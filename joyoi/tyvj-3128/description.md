# 

 
 # 题目描述 
<p>
　　学校实行学分制。每门的必修课都有固定的学分，同时还必须获得相应的选修课程学分。学校开设了N（N<300）门的选修课程，每个学生可选课程的数量M是给定的。学生选修了这M门课并考核通过就能获得相应的学分。<br>　　在选修课程中，有些课程可以直接选修，有些课程需要一定的基础知识，必须在选了其它的一些课程的基础上才能选修。例如《Frontpage》必须在选修了《Windows操作基础》之后才能选修。我们称《Windows操作基础》是《Frontpage》的先修课。每门课的直接先修课最多只有一门。两门课也可能存在相同的先修课。每门课都有一个课号，依次为1，2，3，…。 例如:<br><br><center><img src="/source/joyoi/tyvj-3128/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEyOC9wcm9ibGVtc19pbWFnZXMvMTQxMi8xLmJtcA==.bmp"></img></center><br>　　表中1是2的先修课，2是3、4的先修课。如果要选3，那么1和2都一定已被选修过。 　　你的任务是为自己确定一个选课方案，使得你能得到的学分最多，并且必须满足先修课优先的原则。假定课程之间不存在时间上的冲突。<br></p> 

 
 # 输入格式 
<p>
　　输入文件的第一行包括两个整数N、M（中间用一个空格隔开）其中1≤N≤300,1≤M≤N。<br>　　以下N行每行代表一门课。课号依次为1，2，…，N。每行有两个数（用一个空格隔开），第一个数为这门课先修课的课号（若不存在先修课则该项为0），第二个数为这门课的学分。学分是不超过10的正整数。<br></p> 

 
 # 输出格式 
<p>
　　输出文件每行只有一个数。第一行是实际所选课程的学分总数。以下各行的数，表示所选课程的课号。</p> 

 
 # 提示 
<p>
<br><center><img src="/source/joyoi/tyvj-3128/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEyOC9wcm9ibGVtc19pbWFnZXMvMTQxMi8yLmJtcA==.bmp"></img></center></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td></td><td></td></tr></table>
